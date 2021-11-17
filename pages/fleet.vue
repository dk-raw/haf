<template>
  <div class="container">
    <h1>HAF Fleet</h1>
    <p class="lead">
      fighters, bombers, UAVs, helicopters, anti-air systems and transporters
    </p>
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
      <div class="col">
        <Card
          header="Lockheed F-16C/D/V Block 52+/72 Viper"
          description="State-of-the-art supersonic air superiority fighter armed with AIM-9 Sidewinders, AIM-120 AMRAAMs, AIM-2000s infra red guided, and AGM 88 anti-radiation missiles. It is also equipped with an AN/APG-83 AESA radar, and electronic warfare countermeasures."
          imageUrl="f16-viper.jpg"
          :tags="[{ type: 'Fighter' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Dassault Rafale F3R"
          description="Two seat, twin engine air supremacy fighter jet equipped with a SAGEM-OSF optronique secteur frontal infra red search and track system, RBE2-AA AESA radar and armed with MICA EM and MAGIC-2 infra red active radar data link guided missles as well as MBDA AM 39-Exocet anti-ship missiles."
          imageUrl="rafale.jpg"
          :tags="[{ type: 'Fighter' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Dassault Mirage 2000-5"
          description="Equipped with the Antilope 50 radar, the Damocles forward looking infra red and Thales RDY-2 synthetic aperture radar and armed with MICA EM/MAGIC-2 infra red active radar data link guided missles, ΑΜ-39 EXOCET active radar bombs and 2 SCALP-EG augmenting charge bombs."
          imageUrl="mirage2000.jpg"
          :tags="[{ type: 'Fighter' }, { type: 'Bomber' }]"
        />
      </div>
      <div class="col">
        <Card
          header="McDonnell Douglas F-4 Phantom II"
          description="Long range supersonic fighter bomber armed with an AFDS, CBU-58/71 bombs, Mk 36 Destructor bombs, AGM-65 G infra red, AGM-65 A/B guided missles and GBU-10-12-16 laser guided missles."
          imageUrl="f4-phantom.jpg"
          :tags="[{ type: 'Bomber' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Lockheed Martin F-35 Lightning II"
          description="Soon to be equipped with a APG-81 AESA radar, AAQ-40 E/O targeting system and ASQ-239 Barracuda electronic warfare system and armed with a GAU-22/A 4-barrel rotary cannon, 2 ΑΙΜ-120 B active radar guided missles, 4 AIM-9 Sidewinder missles and 2 AGM-154 infra red bombs."
          imageUrl="f35.jpg"
          :tags="[{ type: 'Fighter' }, { type: 'Bomber' }, { type: 'Stealth' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Lockheed P-3 Orion"
          description="Fitted with a ASQ-81 magnetic anomaly detector, a AN/APS-115 maritime surveillance radar and AN/APS-137D(V)5 inverse synthetic aperture search radar. The Orion is also armed with Mk 46 Mod.5 torpedoes and Mk 55 naval mines for optimal submarine hunting and naval surveillance."
          imageUrl="p-3.jpg"
          :tags="[{ type: 'Support' }, { type: 'Anti-Submarine' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Erieye EMB-145H AEW&C"
          description="Airborne early warning and control (Command & Control) aircraft fitted with an active electronically scanned array radar, anti-submarine warfare system and forward looking infra red system. Capable of data link & voice connections, ELINT intelligence gathering and EMCON."
          imageUrl="emb-145h.jpg"
          :tags="[{ type: 'Support' }, { type: 'Intelligence' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Lockheed C-130 Hercules"
          description="Military transport aircraft capable of transporting heavy payloads over large distances and takeoffs and landings on unprepared runways."
          imageUrl="c-130.jpg"
          :tags="[{ type: 'Support' }, { type: 'Transport' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Alenia C-27J Spartan"
          description="Military transport aircraft capable of transporting heavy payloads over large distances."
          imageUrl="c-27j.jpg"
          :tags="[{ type: 'Support' }, { type: 'Transport' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Boeing CH-47 Chinook"
          description="Twin engine heavy-lift transport helicopter extenively used around the world to transport extremely heavy payloads over large distances."
          imageUrl="chinook.jpg"
          :tags="[
            { type: 'Helicopter' },
            { type: 'Support' },
            { type: 'Transport' },
          ]"
        />
      </div>
      <div class="col">
        <Card
          header="Sikorsky SH-70B Aegean Hawk"
          description="Multi role helicopter used for anti-submarine and anti-surface warfare. Equipped with a pneumatic sonobuoy launcher, a magnetic anomaly detector and forward looking infra red. Armed with MK-46 torpedoes and AGM-119B/AGM-114M guided missles."
          imageUrl="sh-70.jpg"
          :tags="[{ type: 'Helicopter' }, { type: 'Multi Role' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Boeing AH-64 Apache Longbow"
          description="Twin turboshaft attack helicopter featuring target acquisition and designation, a night vision system, infra red countermeasures, a thermographic camera as well as a helmet mounted display. Armed with AGM-114 guided missles and Hydra 70 rocket pods."
          imageUrl="apache.jpg"
          :tags="[{ type: 'Helicopter' }, { type: 'Attack Helicopter' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Eurocopter AS332C1 Super Puma"
          description="Multi role utility helicopter equipped with anti-submarine warfare and anti-surface warfare systems including a sonar and Omera search radar. Greece also operate search and rescue variants of the helicopter."
          imageUrl="super-puma.jpg"
          :tags="[{ type: 'Helicopter' }, { type: 'Multi Role' }]"
        />
      </div>
      <div class="col">
        <Card
          header="IAI Heron UAV"
          description="Long endurance reconnaissance unmaned aerial vehicle capable of operations of up to 52 hours. Equiped with a airborne ground surveillance, thermographic, COMINT and ELINT systems while capable of target acquisition and artillery guidance."
          imageUrl="iai-heron.jpg"
          :tags="[
            { type: 'UAV' },
            { type: 'Support' },
            { type: 'Intelligence' },
          ]"
        />
      </div>
      <div class="col">
        <Card
          header="SAGEM Sperwer"
          description="Short range reconnaissance unmaned aerial vehicle capable of sending back images of enemy infrastructure to it's base. The Sperwer has a 5 hour endurance."
          imageUrl="sagem-sperwer.jpg"
          :tags="[{ type: 'UAV' }, { type: 'Intelligence' }]"
        />
      </div>
      <div class="col">
        <Card
          header="E1-79 Pegasus II"
          description="Long endurance over-battlefield reconnaissance and intelligence surveillance unmaned aerial vehicle also capable fo ELINT. The Pegasus has a 15 hour range and can easily operate over the battlefield."
          imageUrl="pegasus.jpg"
          :tags="[{ type: 'UAV' }, { type: 'Intelligence' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Raytheon MIM-104 Patriot"
          description="Remotely controled HSAM with an 150km interception range. Capable of intercepting up to 9 ballistic, tactical, cruise missles or fighter jets. It can be armed either with MIM-104D GEM/MIM-104B SOJC or MIM-104A supersonic 90kg warhead missles. It is also equipped with a AN/MPQ-65 long range radar set."
          imageUrl="mim-patriot.jpg"
          :tags="[{ type: 'HSAM' }, { type: 'ABM' }]"
        />
      </div>
      <div class="col">
        <Card
          header="NPO Almaz S-300 PMU1"
          description="HSAM capable of protecting a large area by intercepting up to 4 fighter jets or ballistic, tactical, cruise missles at a time. Equipped with RSR and SSR radars and armed with 4 long range 48Ν6Ε TVM 150kg warhead missles."
          imageUrl="s-300.jpg"
          :tags="[{ type: 'HSAM' }, { type: 'ABM' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Thomson CSF Matra Crotale NG"
          description="Infra red differential ecartometry short range anti-ship and anti-aircraft system armed with VT-1 supersonic 18kg warhead missles and equipped with a S-band pulse doppler radar and Ku-band TWT tracking radar. Thermal camera, CCD camera and IR Localizer are fitted for optimal missle interception."
          imageUrl="crotale-ng.jpg"
          :tags="[{ type: 'SHORAD' }, { type: 'ASM' }]"
        />
      </div>
      <div class="col">
        <Card
          header="TOR M1"
          description="High accuracy short range SAM caplable of destroying airplanes, helicopters, cruise missiles, precision guided munitions, UAVs and short range ballistic threats. Armed with 4 15kg warhead radar controlled proximity fuzed missles. Capable of intercepting up to 2 targets simultaneously."
          imageUrl="tor-m1.jpg"
          :tags="[{ type: 'SHORAD' }, { type: 'ASM' }]"
        />
      </div>
      <div class="col">
        <Card
          header="9K33 Osa"
          description="High accuracy short range tactical SAM equipped with a 1S51M3-2 radar consisting of a J band parabolic dish antenna, an elliptical rotating surveillance antenna and a large pulsed J band engagement antenna making it ideal for short range applications."
          imageUrl="9k33-osa.jpg"
          :tags="[{ type: 'SHORAD' }, { type: 'ASM' }]"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Fleet",
  data() {
    return {};
  },
};
</script>
