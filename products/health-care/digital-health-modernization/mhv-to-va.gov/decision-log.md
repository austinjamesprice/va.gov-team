# MHV to VA.gov Decision Log
Please log key MHV to VA.gov decisions related to the below practice areas, including date, who made the decision, a description of the decision and any specific rationale behind it.  For decisions about specific products, please use the decision log within that products document folder.

## Product
| Date | Decision Maker(s) | Description of Decision | Rationale |
|------|-------------------|-------------------------|-----------|
|2022/10/18|Lauren Alexanderson, David Conlon, Danielle Thierry|Unauth content will not be a priority for now|There are a lot of dependencies for this currently, and our main focus is migrating the apps|
|      |Lauren Alexanderson|Medical Records will be built domain by domain|This will allow the teams to more quickly show progress|
|      |Lauren Alexanderson, Coulton Bunney|The first domain to be created will be Immunizations|This one is relatively straightforward and a good one to start with|
|      |Lauren Alexanderson, Leah Bannon|The second and third domains will be Labs & Tests and Notes|           |
| 2023/01/29     |Erick Spahn, Maureen Layden                   |Medications will be rolled in with Pharmacy as a new section of the health portal.          | Veterans will be able to see current and past medications and request refills in one place. This structure has been confirmed by tree testing research, implied by GAO reports, supported by common sense.        |
|2023/02/02      |Lauren Alexanderson                   |Links to Appointments will point to VAOS, not MHV                         |Good way to start the soft retirement of Appointments on MHV           |
|02/08/2023     | Lauren Alexanderson, Patrick Bateman        | Name of the VFS product for the landing page, navigation and other shared elements will be *MHV on VA.gov Portal*  | The work must have a name to do a Collaboration Cycle kick-off, and this is a good "umbrella" name.|
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |

## Functional (How it works)
| Date          | Decision Maker(s).                          | Description of Decision                                                             | Rationale                                                                           |
|---------------|---------------------------------------------|-------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
|10/6/2022      | Dr. Evans, Chris Johnston                   | Health Portal should be consistent with the flagship mobile app as much as possible | Consistency will keep users from having to learn two different mental models.  Portal can also glean knowledge from things Mobile has already implemented.          |
|02/08/2023      |Lauren Alexanderson, Dave Conlon, Patrick Bateman  |"My Health" button in authenticated VA.gov main nav will be changed to "My Health*e*Vet |In the future, we’re sticking with the My HealtheVet branding on VA.gov, so the link text should match.           |


## Design (How it looks)
| Date | Decision Maker(s) | Description of Decision | Rationale |
|------|-------------------|-------------------------|-----------|
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |


## Research (How it tests)
| Date | Decision Maker(s) | Description of Decision | Rationale |
|------|-------------------|-------------------------|-----------|
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |

## Content & IA
| Date | Decision Maker(s) | Description of Decision | Rationale |
|------|-------------------|-------------------------|-----------|
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |

## Engineering
| Date | Decision Maker(s) | Description of Decision | Rationale |
|------|-------------------|-------------------------|-----------|
| 01/24/2023 | Eric Voshall | We will use the Ruby Prawn PDF library for creating shareable PDFs of immunization records. | Prawn has a lot of examples of usage within `vets-api` - there is no front-end PDF generation library recommended for use on `vets-website`. |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |
|      |                   |                         |           |


