## Registration

An affiliate or member can utilise the Soteria self-signup with approval
for a verified researcher role in the Soteria COU.

### Steps

1. Find the requirements that you meet [below](#requirements).
1. Fill out the application [form](http://soteria.osg-htc.org/account) on your account page, found under actions.
1. Wait for your approval. We will create a ticket, and follow up with any further questions by email.

### Requirements

Before completing the Researcher application form please confirm both of the following applies.

1. __Researcher email address is associated with a US university or research institution that receives federal funding.__  
    - Lookup institutions here: [https://www.nsf.gov/statistics/srvyfedsupport](https://www.nsf.gov/statistics/srvyfedsupport)
2. __One of the following applies__:
    - Active XRAC allocation
        - The user has an active XRAC allocation.
        - No additional information needed for verification.
    - Institute Member and Recently Published
        - Researcher is listed as faculty or scientist/researcher in a department at the institution 
          on an institutional website AND they have a publication from within the last 2 years listed 
          in their public ORC ID profile. 
        - Website URL and Publication DOI required for verification.
    - Active Federal Grant on ORCID Profile
        - Researcher is listed as having an active grant through that institution from a US federal 
          government funding agency AND the grant shows up in their public ORC ID profile.
        - Grant # and Funding Agency required for approval.
    - Non R1, HBCU, or TCU institute member
        - Researcher is listed as faculty or scientist/researcher in a department at the institution on 
          an institutional website AND the institution is non-R1, HBCU, or TCU.  
        - Website URL of institution staff page, and institution classification required for verification.
    - SOTERIA PI approval
        - Exemption from the above approved by SOTERIA PI.
        - No additional information needed for verification.
      
### Timeline

On approval Researcher status is given for 2 years, after which re-enrollment will need to occur.

## Projects

### Allocation

Researcher status comes with advanced project allocations.

| Size  | # of Public | # of Private | Timeline |
|-------|-------------|--------------|----------|
| 100GB | 3           | 2            | 2 Years ( +2 Years for each re-enrollment )  |

!!! note 
    More projects can be allocated by [requesting an additional project allocation](#request-additional-project-allocation).

### Permissions

Each project will get three corresponding OSG groups created with the verified researcher as the administrator.

- __sotera-<project name\>-guests__
    - Individuals who are limited guests of the project (read-only).
- __soteria-<project name\>-developers__ 
    - Individuals who are developers of the project (read/write).
- __soteria-<project name\>-maintainers__ 
    - Individuals who are maintainers of the project (read/write + delete)
- Project tag immutability and retention rules are configured:
    - dev-* tags are limited to 90 days
    - Immutability rules are setup for all but “latest” tag for repo.

## Actions

- [Create a Project](#create-a-project)

    
- [Managing Project Members](#adding-project-members)

### Create a Project

All researchers can create project up to the base allocation. All projects after that will need to be created by OSG 
staff on request. 

On creation of the project the researcher will find they own 3 new permission groups in COmanage as [highlighted above](#permissions).
It is here that you will allow new users to use your project. Additional management can be found in the 

### Managing Project Members

Project member management is orchestrated using your groups [COmanage app](https://registry.cilogon.org/registry/co_groups/index/co:8/search.member:1/search.owner:1). 

On opening your groups tab you will find 4 groups for each project:

- soteria-<project-name\>-owners
- soteria-<project-name\>-maintainers
- soteria-<project-name\>-developers
- soteria-<project-name\>-guests

Each of these 4 groups corresponds to a [Harbor User Permission Level](https://goharbor.io/docs/1.10/administration/managing-users/user-permissions-by-role/).
By adding a member to one of these groups you will be providing them with the corresponding level of access to the indicated project.

!!! note

    soteria-<project-name\>-owners is used by Soteria Staff to keep track of researchers project allocations and is not editable by the researcher.

#### Adding a Member to a Project

1. Have the member register for Soteria

    [Register for Soteria](https://soteria.osg-htc.org/registration)

1. Decide the level of Project access you would like to provide them with (maintainer, developer, guest)

    [Harbor User Permission Levels](https://goharbor.io/docs/1.10/administration/managing-users/user-permissions-by-role/)

1. Find the corresponding group in COmanage

    1. Navigate to the COmanage Group page to see your groups

        [COmanage User Group Page](https://registry.cilogon.org/registry/co_groups/index/co:8/search.member:1/search.owner:1)

    1. Find the permission group relating to the project and access level

        The group name will be soteria-<project-name\>-<access-level\>

    1. Click "Members" under the actions column

    1. Search for the new member in the "Add Member:" search bar and click "ADD"

    1. (Optional) If you would like this new member to manage members of this group you can toggle the "owner" checkbox

1. Have the new member re log into harbor for the new access level to take effect






