# Data Overview: Airport Datasets

If you are working on scenario 1 or 2, you will be working on airfield data.

For these scenarios, imagine you are a data scientist tasked with reviewing data about various airports, heliports, and seaplane bases collected by a new field data collector in the U.S. state of Alaska for the purposes of curating a clean, tidy, and organized informational chart about these airfields for professionals.

You have some domain experience with airfields but may have a low to moderate understanding of the geography in Alaska. 

Your job is to flag down any inconsistencies or errors you see in the data provided to you so that flight planners and airspace professionals have accurate information on the airfields in the state when managing the skies.

---

## **Attribute Definitions**
NOTE: Depending on which scenario you are working on, you may only see some of these attributes.
- **type**: The type of airfield, i.e. is it an airport, heliport, or seaplane base?
  - Possible Values:
    - **AIRPORT**: Airfields that serve passenger and cargo airplanes and other airples.
    - **HELIPORT**: Airfields that serve helicopters.
    - **SEAPLANE BASE**: Airfields that serve seaplanes. Seaplane bases are usually located on water, such as lakes, rivers, bays, or harbors.
- **region**: The region of Alaska the airfield is located in.
- **facilityname**: The name of the airfield.
- **owner**: The person, group, or entity that owns the airfield.
- **ownertype**: The type of owner that owns the airfield
  - Possible Values:
    - **GOV**: Owned by a government entity or agency, such as a city or state, or a government-run entity.
    - **PUBLIC**: Publicly owned and/or officially set aside for public use.
    - **INDIVIDUAL**: Owned by a single person, a couple of people, or a family.
    - **GROUP**: Owned by a group of people (e.g. a tribe) or an organization.
    - **CORP**: Owned by a business or other corporation.
- **manager**: The person/people or entity that manages/oversees the day-to-day function of this particular airfield. NOTE: Some airfields do not have a manager. These examples use a manager value of "NO MANAGER," and an occurrence of "NO MANAGER" does not necessarily mean the value is an error.
