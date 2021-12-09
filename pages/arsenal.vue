<template>
  <div class="container">
    <h1>HAF Arsenal</h1>
    <p class="lead">AA/AG/Anti-Ship missles, AG bombs and Pods</p>
    <hr />
    <div
      class="
        row
        row-cols-1
        row-cols-xxl-4
        row-cols-xl-3
        row-cols-lg-2
        row-cols-md-2
        row-cols-sm-1
        g-4
        mb-4
      "
    >
      <div class="col" v-for="weapon in weapons" :key="weapon.id">
        <WeaponCard
          :header="weapon.name"
          :code="weapon.code"
          :imageUrl="weapon.imageUrl"
        />
      </div>
    </div>
    <h4 class="display-6">Other</h4>
    <ul class="px-3" style="list-style: inside">
      <li>DB-110</li>
      <li>LANTIRN-AWNP</li>
      <li>LANTIRN-TP</li>
      <li>LITENING targeting pod</li>
      <li>ASTAC ELINT-SIGINT</li>
      <li>Sniper ATP</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      weapons: [
        {
          name: "AIM-9-L/I/I1/M/P4/J Sidewinder",
          code: "FOX 2",
          imageUrl: "aim-9.jpg",
        },
        {
          name: "AIM-120-C-5/C-7/B AMRAAM",
          code: "FOX 3",
          imageUrl: "aim-120.jpg",
        },
        {
          name: "AIM-2000 IRIS-T",
          code: "FOX 2",
          imageUrl: "aim-2000.jpg",
        },
        {
          name: "R550 Magic-II",
          code: "FOX 2",
          imageUrl: "magic-2.jpg",
        },
        {
          name: "MBDA MICA-EM",
          code: "FOX 3",
          imageUrl: "mica-em.jpg",
        },
        {
          name: "MBDA MICA-IIR",
          code: "FOX 2",
          imageUrl: "mica-iir.jpg",
        },
        {
          name: "MBDA METEOR BVRAAM",
          code: "FOX 3",
          imageUrl: "meteor.jpg",
        },
        {
          name: "CBU-58/71",
          code: "PICKLE",
          imageUrl: "cbu-58.jpg",
        },
        {
          name: "GBU-50 EP II",
          code: "PAVEWAY",
          imageUrl: "gbu-50.jpg",
        },
        {
          name: "GBU-24 PW III",
          code: "PAVEWAY",
          imageUrl: "gbu-24.jpg",
        },
        {
          name: "AGM-65A/B/G",
          code: "RIFLE",
          imageUrl: "agm-65.jpg",
        },
        {
          name: "AGM-88 HARM",
          code: "MAGNUM",
          imageUrl: "agm-88.jpg",
        },
        {
          name: "AGM-154",
          code: "JSOW",
          imageUrl: "agm-154.jpg",
        },
        {
          name: "SCALP-EG",
          code: "PICKLE",
          imageUrl: "scalp.jpg",
        },
        {
          name: "AM-39 EXOCET",
          code: "BRUISER",
          imageUrl: "am-39.jpg",
        },
        {
          name: "BLU-109",
          code: "PICKLE",
          imageUrl: "blu-109.jpg",
        },
        {
          name: "GBU-8A/B HOBOS",
          code: "PAVEWAY",
          imageUrl: "gbu-8.jpg",
        },
        {
          name: "GBU-10/12/16",
          code: "PAVEWAY",
          imageUrl: "gbu-16.jpg",
        },
        {
          name: "GBU-10/12/16",
          code: "JDAM",
          imageUrl: "gbu-31.jpg",
        },
        {
          name: "MK-20 ROCKEYE",
          code: "PICKLE",
          imageUrl: "mk-20.jpg",
        },
        {
          name: "MK-36 Destructor",
          code: "PICKLE",
          imageUrl: "mk-36.jpg",
        },
      ],
    };
  },
};
</script>
