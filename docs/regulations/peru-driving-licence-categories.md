# Peru Driving Licence Categories — Source Translation

## Status and provenance

English translation of `docs/En el Perú el Ministerio.txt` at commit `0485553df7fcaa967f9b5cd472307cafafbea9b8`, structured on 7 October 2026. The Spanish original is preserved in Git history. The translation retains the introductory classification, all six Class A categories, all four Class B categories, numerical thresholds and the hazardous-materials section.

Sections marked **Source translation** reproduce the supplied text rather than establish current eligibility or legal authorization. The editorial review below records discrepancies and verification limits separately. This is a reference note, not an implemented licence-management module or an authorization for autonomous vehicle operation.

## Source translation: classification overview

In Peru, the Ministry of Transport and Communications (MTC) classifies driving licences, known as *brevetes*, into two main classes: Class A for vehicles with four or more wheels and Class B for vehicles with two or three wheels. These are divided into categories and subcategories according to vehicle type, passenger capacity, gross weight and purpose (private use or public/commercial transport).

## Source translation: Class A — vehicles with four or more wheels

These licences cover cars, light trucks, buses, trucks and heavy machinery. To qualify for professional categories, from A-IIa onwards, drivers must first hold an initial A-I licence and meet the required prior-licence holding period through progressive upgrading/recategorization.

### A-I — private use / entry category

- **Authorized vehicles:** sedans, hatchbacks, coupes, SUVs, station wagons, pickup trucks, vans and dune buggies exclusively for private use.
- **Requirements:** minimum age 18, a medical examination, a traffic-rules examination and a practical driving test.
- **Validity stated by the source:** 10 years on first issue and 5 years on renewal. See the editorial correction below.

### A-II — light professional vehicles and medium passenger transport

#### A-IIa — passenger transport / service

- **Vehicles:** those covered by A-I, plus vehicles used for taxi services, urban public/shared passenger transport, ambulances and school transport.
- **Requirements:** minimum age 21 and at least 2 years of experience holding an A-I licence.

#### A-IIb — microbuses, minibuses and light freight

- **Vehicles:** those covered by A-I and A-IIa, plus microbuses with up to 16 seats and a maximum gross weight of 4 tonnes, and minibuses with up to 33 seats and a maximum gross weight of 7 tonnes.
- **Requirements:** minimum age 24 and at least 3 years holding an A-I licence, or 1 year holding A-IIa.

### A-III — heavy professional vehicles: buses and trucks

#### A-IIIa — large buses

- **Vehicles:** urban, interurban, interprovincial, panoramic and articulated buses with a gross weight above 6 tonnes; includes vehicles covered by A-I, A-IIa and A-IIb.
- **Requirements:** minimum age 24 and at least 2 years holding A-IIb.

#### A-IIIb — heavy freight and trailers

- **Vehicles:** those covered by A-I, A-IIa and A-IIb, plus chassis-cab vehicles, trailers, semitrailers, cranes, platform trucks, dump trucks and tankers. It does not authorize A-IIIa buses.
- **Requirements:** minimum age 24 and at least 2 years holding A-IIb.

#### A-IIIc — highest special licence category

- **Vehicles:** the source describes this as the most comprehensive category, covering all vehicles in A-I, A-IIa, A-IIb, A-IIIa and A-IIIb.
- **Requirements:** minimum age 27 and at least 4 years holding A-IIb, or at least 1 year holding A-IIIa or A-IIIb.

## Source translation: Class B — smaller vehicles with two or three wheels

The source states that this class is managed primarily through provincial municipalities, in coordination with the MTC for registration in the National Driver System (*Sistema Nacional de Conductores*).

| Category | Source vehicle scope |
| --- | --- |
| B-I | Non-motorized three-wheeled vehicles (tricycles) intended for special public passenger or freight transport. |
| B-IIa | Mopeds and similar light motorized vehicles. |
| B-IIb | Two-wheeled motorcycles and three-wheeled motorcycles with sidecars for private use, delivery or goods transport. |
| B-IIc | All B-IIa and B-IIb vehicles, plus motorcycle taxis and motor tricycles authorized for commercial public passenger transport. |

## Source translation: special authorization — hazardous materials and waste

The source describes this as a Special Operating Permit / Renewal rather than an independent licence class.

- **Application:** mandatory for drivers transporting fuels, explosives, chemical inputs, compressed gases or hazardous waste on national roads.
- **Requirement:** added to professional freight licences (A-IIb, A-IIIb or A-IIIc) after passing a specific theoretical and practical training course covering MATPEL (hazardous materials) rules and first aid.

## Editorial review and official references

Review date: 7 October 2026. This limited review distinguishes the translated source from official guidance; it does not resolve all current legal requirements for a particular vehicle, driver or service. Some official pages were available as indexed text; direct retrieval of the recategorization page failed.

| Topic | Editorial finding | Official reference |
| --- | --- | --- |
| A-I renewal validity | The blanket five-year renewal statement is inaccurate. MTC guidance gives 10, 8 or 5 years according to the driver's sanction record. Do not use the translated sentence as a universal renewal rule; check other applicable conditions, including age. | [MTC renewal guidance](https://www.gob.pe/191-renovar-o-revalidar-la-licencia-de-conducir-brevete) |
| Class/category scope | The MTC overview supports the broad class structure but does not exactly match every vehicle example in the source. In particular, its B-I description refers to special public passenger transport, while the source adds freight; its B-IIb description also includes B-IIa vehicles. Treat the source's lists as a summary requiring vehicle-specific verification. | [MTC licence types](https://www.gob.pe/262-tipos-de-licencia-de-conducir-brevete-tipos-de-licencia-de-conducir-brevete) |
| Recategorization | The source's A-IIIc route (age 27; 4 years of A-IIb or 1 year of A-IIIa/A-IIIb) agrees with indexed MTC guidance. This check does not establish a complete application checklist for all categories. | [MTC recategorization guidance](https://www.gob.pe/es/288-recategorizacion-de-licencia-de-conducir-brevete) |
| Hazardous-materials authorization | The driver's special authorization is additional to the vehicle-appropriate licence. It should not be conflated with the transport operator's operating permit or vehicle authorization. Official service guidance also calls for medical/psychological evaluation and basic training; the source's training-only description is incomplete. | [MTC driver authorization information](https://www.gob.pe/institucion/mtc/informes-publicaciones/345123-autorizacion-especial-para-transportar-materiales-y-residuos-peligrosos) and [government application guidance](https://www.gob.pe/31747-obtener-autorizacion-especial-para-transportar-materiales-y-residuos-peligrosos?child=64662) |

The source's broad references to heavy machinery, school/public transport, semitrailers, tankers, the exact MATPEL course content and national-road scope were preserved but not individually established against a consolidated current regulation. Neither a category label nor a vehicle example by itself establishes every operating permission required for a transport service.

## Relationship to jfxai4mass

This note supplies human-driver licensing context for the project's mobility reference architecture. Mapping these categories into a simulation or future data model would require separate verification of vehicle classes, operating purposes and applicable rules. It does not certify a vehicle, authorize public-road testing or demonstrate autonomous-system compliance.

[Documentation index](../README.md) · [Migration register](../MIGRATION-REGISTER.md) · [Project overview](../../README.md)
