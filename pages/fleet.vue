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
          header="Lockheed F-16C/D/V Block 30/40/50/52+/72 Viper"
          description="State-of-the-art supersonic air superiority fighter armed with AIM-9 Sidewinders, AIM-120 AMRAAMs, AIM-2000s infra red guided, and AGM 88 anti-radiation missiles. It is also equipped with an AN/APG-83 AESA radar, and electronic warfare countermeasures."
          imageUrl="f16-viper.jpg"
          :tags="[{ type: 'Fighter' }, { type: 'Multi-role' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Dassault Rafale B/C F3R"
          description="4.5 gen air supremacy fighter jet equipped with a SAGEM-OSF optronique secteur frontal IRIS-T system, a long-range RBE2-AA AESA radar and armed with 4 METEOR BVRAAM datalink missiles, 2 SCALP-EGs cruise missiles and AM-39 EXOCET blk 2 anti-ship missiles."
          imageUrl="rafale.jpg"
          :tags="[{ type: 'Fighter' }, { type: 'Multi-role' }]"
        />
      </div>
      <div class="col">
        <Card
          header="McDonnell Douglas F-4E Phantom II PI 2000"
          description="Long range supersonic fighter bomber armed with an AFDS, CBU-58/71 bombs, Mk 36 Destructor bombs, AGM-65 G infra red, AGM-65 A/B guided missles and GBU-10-12-16 laser guided missles."
          imageUrl="f4-phantom.jpg"
          :tags="[{ type: 'Bomber' }, { type: 'Attack' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Dassault Mirage 2000-5 Mk II"
          description="Equipped with the Antilope 50 radar, the Damocles forward looking infra red and Thales RDY-2 synthetic aperture radar and armed with MICA EM/MAGIC-2 infra red active radar data link guided missles, ΑΜ-39 EXOCET anti-ship missiles and 2 SCALP-EG augmenting charge bombs."
          imageUrl="mirage2000-5.jpg"
          :tags="[{ type: 'Fighter' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Lockheed Martin F-35 Lightning II"
          description="Soon to be equipped with a APG-81 AESA radar, AAQ-40 E/O targeting system and ASQ-239 Barracuda electronic warfare system and armed with a GAU-22/A 4-barrel rotary cannon, 2 ΑΙΜ-120 B active radar guided missles, 4 AIM-9 Sidewinder missles and 2 AGM-154 infra red bombs."
          imageUrl="f35.jpg"
          :tags="[{ type: 'Fighter' }, { type: 'Multi-role' }, { type: 'TBA' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Erieye EMB-145H AEW&C"
          description="Airborne early warning and control (Command & Control) aircraft fitted with an active electronically scanned array radar, anti-submarine warfare system and forward looking infra red system. Capable of data link & voice connections, ELINT intelligence gathering and EMCON."
          imageUrl="emb-145h-awacs.jpg"
          :tags="[{ type: 'AWACS' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Lockheed C-130/H Hercules"
          description="Military transport aircraft capable of transporting heavy payloads over large distances and takeoffs or landings on unprepared and unpaved runways. The Hellenic Air Force operates 2 C-130H EW variants used for electronic warfare and early warning and control."
          imageUrl="c-130.jpg"
          :tags="[{ type: 'Tactical Transport' }, { type: 'EW' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Alenia C-27J Spartan"
          description="Military transport aircraft capable of transporting heavy payloads over large distances. It's maximum is payload weight is around 11,6 tons and features 2 Rolls-Royce AE2100-D2A turboprop engines wwith a combined thrust of 6,916 kW and a 1,759 km range."
          imageUrl="c-27j.jpg"
          :tags="[{ type: 'Tactical Transport' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Lockheed P-3B Orion"
          description="Fitted with a ASQ-81 magnetic anomaly detector, a AN/APS-115 maritime surveillance radar and AN/APS-137D(V)5 inverse synthetic aperture search radar. The Orion is also armed with Mk 46 Mod.5 torpedoes and Mk 55 naval mines for optimal submarine hunting and naval surveillance."
          imageUrl="p-3b.jpg"
          :tags="[{ type: 'Navy Air Force' }, { type: 'Anti-Submarine' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Sikorsky SH-70B6/MH-60R Aegean Hawk"
          description="Multi role helicopter used for anti-submarine and anti-surface warfare. Equipped with a pneumatic sonobuoy launcher, a magnetic anomaly detector and forward looking infra red. Armed with MK-46 torpedoes and AGM-119B/AGM-114M guided missles."
          imageUrl="sh-70.jpg"
          :tags="[
            { type: 'Navy Air Force' },
            { type: 'Helicopter' },
            { type: 'Anti-Submarine' },
          ]"
        />
      </div>
      <div class="col">
        <Card
          header="Boeing CH-47 Chinook"
          description="Twin engine heavy-lift transport helicopter extenively to transport extremely heavy payloads over large distances. It features 2 Lycoming T55-GA-714A turboshaft engines with a combined power output of 7,458 kW. The CH-47 can achieve speeds of up to 170 knots."
          imageUrl="chinook.jpg"
          :tags="[
            { type: 'Army Air Force' },
            { type: 'Helicopter' },
            { type: 'Tactical Transport' },
          ]"
        />
      </div>
      <div class="col">
        <Card
          header="Boeing AH-64A/D Apache Longbow"
          description="Twin turboshaft attack helicopter featuring target acquisition and designation, a night vision system, infra red countermeasures, a thermographic camera as well as a helmet mounted display. Armed with AGM-114 guided missles and Hydra 70 rocket pods."
          imageUrl="apache.jpg"
          :tags="[
            { type: 'Army Air Force' },
            { type: 'Helicopter' },
            { type: 'Attack' },
          ]"
        />
      </div>
      <div class="col">
        <Card
          header="Bell OH-58D Kiowa"
          description="Armed military helicopter used for observation and reconnaissance over the battlefield. It is armed with Hydra 70 rocket pods and AGM-114 guided missles. The craft is also fitted with a thermal imaging and laser range finder/designator system as well as a passive wire strike protection system."
          imageUrl="bell-oh58.jpg"
          :tags="[
            { type: 'Army Air Force' },
            { type: 'Helicopter' },
            { type: 'Reconnaissance' },
            { type: 'Attack' },
          ]"
        />
      </div>
      <div class="col">
        <Card
          header="NHIndustries NH90 TTH"
          description="Multi role utility military helicopter primarily used for tactical transport fitted with a full fly-by-wire system, infrared suppression system, wire strike protection system, forward looking infrared, helmet mounted display. The NH90 possesses the lowest radar signature in its class."
          imageUrl="nh-90.jpg"
          :tags="[
            { type: 'Army Air Force' },
            { type: 'Helicopter' },
            { type: 'Tactical Transport' },
          ]"
        />
      </div>
      <div class="col">
        <Card
          header="Eurocopter AS332C1 Super Puma"
          description="Multi role utility helicopter primarily used for combat search and rescue and medical evacuation. The helicopter is equipped with a forward looking infrared, Omera search radar and a sonar system. The Super Puma has a maximum speed of 150 knots."
          imageUrl="super-puma.jpg"
          :tags="[{ type: 'Helicopter' }, { type: 'Multi Role' }]"
        />
      </div>
      <div class="col">
        <Card
          header="IAI Heron TP"
          description="Long endurance unmaned combat aerial vehicle capable of operations of up to 30 hours when fully armed. Armed with SPIKE NLOS anti-tank guided missile with a maximum range of 25km, the Heron TP has a service ceiling of 46,000 feet."
          imageUrl="heron-tp.jpg"
          :tags="[{ type: 'UAV' }, { type: 'UCAV' }]"
        />
      </div>
      <div class="col">
        <Card
          header="General Atomics MQ-9 Reaper"
          description="Unmaned combat aerial vehicle with the a maximum payload of 1,700kg and a maximum speed of 260 knots. It can be armed with up to 8 AGM-114 ATGMs or 4 GBU-12 laser guided bombs. The MQ-9 also features an AN/DAS-1 MTS-B electro-optical targeting system, AN/APY-8 Lynx II radar, SATCOM and autonomous flight."
          imageUrl="mq-9.jpg"
          :tags="[{ type: 'UAV' }, { type: 'UCAV' }, { type: 'TBA' }]"
        />
      </div>
      <div class="col">
        <Card
          header="IAI Heron"
          description="Long endurance reconnaissance unmaned aerial vehicle capable of operations of up to 52 hours. Equiped with a airborne ground surveillance, thermographic, COMINT and ELINT systems while capable of target acquisition and artillery guidance."
          imageUrl="iai-heron.jpg"
          :tags="[{ type: 'UAV' }, { type: 'Reconnaissance' }]"
        />
      </div>
      <div class="col">
        <Card
          header="SAGEM Sperwer"
          description="Short range reconnaissance unmaned aerial vehicle capable of sending back images of enemy infrastructure to it's base as well as targeting artillery fire. The Sperwer has a 5 hour endurance."
          imageUrl="sagem-sperwer.jpg"
          :tags="[
            { type: 'Army Air Force' },
            { type: 'UAV' },
            { type: 'Reconnaissance' },
          ]"
        />
      </div>
      <div class="col">
        <Card
          header="HAI Pegasus II"
          description="Long endurance over-battlefield reconnaissance and intelligence surveillance unmaned aerial vehicle also capable fo ELINT. The Pegasus has a 15 hour range and can easily operate over the battlefield."
          imageUrl="pegasus.jpg"
          :tags="[{ type: 'UAV' }, { type: 'Reconnaissance' }]"
        />
      </div>
      <div class="col">
        <Card
          header="MIM-104 Patriot PAC-3"
          description="Remotely controled SAM with a 150km range. Capable of intercepting up to 9 ballistic, tactical, cruise missles or aircraft at a time. It can be armed either with MIM-104D/B SOJC or MIM-104A supersonic 90kg warhead missles. It is also equipped with a AN/MPQ-65 AESA long range radar set."
          imageUrl="patriot-pac3.jpg"
          :tags="[{ type: 'SAM' }]"
        />
      </div>
      <div class="col">
        <Card
          header="S-300 PMU1"
          description="HSAM capable of protecting a large area by intercepting up to 4 fighter jets or ballistic, tactical, cruise missles at a time at a range of 120km. It is equipped with RSR and SSR radars and armed with 4 long range 48Ν6Ε TVM 150kg warhead missles per launcher."
          imageUrl="s300-pmu1.jpg"
          :tags="[{ type: 'SAM' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Skyguard VELOS"
          description="Short range, all-weather, air defence system composed of 4 RIM-7M Sparrow missile launchers, 4 twin 35mm Oerlikon GDF guns, a SUPER GIRAFFE search radar and 2 SKYGUARD track radars. The VELOS can engage up to 6 targets a time at a range of 19km."
          imageUrl="velos.jpg"
          :tags="[{ type: 'SHORAD' }, { type: 'SAM' }]"
        />
      </div>
      <div class="col">
        <Card
          header="Crotale NG"
          description="Infra red differential ecartometry short range anti-ship and anti-aircraft system armed with VT-1 supersonic 18kg warhead missles and equipped with a S-band pulse doppler radar and Ku-band TWT tracking radar. Thermal camera, CCD camera and IR Localizer are fitted for optimal missle interception."
          imageUrl="crotale-ng.jpg"
          :tags="[{ type: 'SHORAD' }, { type: 'SAM' }]"
        />
      </div>
      <div class="col">
        <Card
          header="TOR M1"
          description="High accuracy short range SAM caplable of destroying airplanes, helicopters, cruise missiles, precision guided munitions, UAVs and short range ballistic threats. Armed with 4 15kg warhead radar controlled proximity fuzed missles. Capable of intercepting up to 2 targets simultaneously."
          imageUrl="tor-m1.jpg"
          :tags="[{ type: 'SHORAD' }, { type: 'SAM' }]"
        />
      </div>
    </div>
    <hr />
    <small class="text-muted">
      *this list includes equipment belonging to the Hellenic Navy and Hellenic
      Army
    </small>
  </div>
</template>

<script>
export default {
  name: "Fleet",
  loading: {
    color: "red",
    height: "5px",
  },
  data() {
    return {
      fleet: [
        {
          name: "Lockheed F-16C/D/V Block 30/40/50/52+/72 Viper",
          description:
            "State-of-the-art supersonic air superiority fighter armed with AIM-9 Sidewinders, AIM-120 AMRAAMs, AIM-2000s infra red guided, and AGM 88 anti-radiation missiles. It is also equipped with an AN/APG-83 AESA radar, and electronic warfare countermeasures.",
          imageUrl: "f-16-viper.jpg",
          tags: [{ type: "Fighter" }, { type: "Bomber" }],
        },
      ],
    };
  },
};
</script>
