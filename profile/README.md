# **Student Life Committee (SLC) - IIIT Hyderabad**

The Student Life Committee enhances the overall student experience and fosters a vibrant and inclusive campus community. We believe that student life is an integral part of a well-rounded education, and we strive to create opportunities for personal growth, leadership development, and meaningful connections among students.

Our committee consists of passionate student representatives who work closely with faculty, staff, and the wider student body to organize and coordinate a wide range of events, programs, and initiatives. From social gatherings and cultural celebrations to educational workshops and community service projects, we aim to provide diverse opportunities for students to explore their interests, build lasting friendships, and make a positive impact on campus.

# **Clubs Council - IIIT Hyderabad**

The Clubs Council is the largest student administrative organization at IIIT Hyderabad and acts as an umbrella body of all the institute-affiliated and associate student-led clubs, groups & societies.

---

## Current Maintainers
- [Bhav Beri](https://github.com/bhavberi)
- [Adari Dileepkumar](https://github.com/Dileepadari)
- [Abhiram Tilak](https://github.com/abhiramtilakiiit)
- [Shreyansh](https://github.com/The-Broken-Keyboard)
- [Evan Bijoy](https://github.com/EvanBijoy)
- [Vishva Saravanan](https://github.com/v15hv4)

##  Deployment Status
> Main Website
>
> [![Better Uptime Badge](https://betteruptime.com/status-badges/v3/monitor/ikqm.svg)](https://clubs_iiith.betteruptime.com/)

[clubs.iiit.ac.in](https://clubs.iiit.ac.in/)

Website `v2` released in April, 2023.

> Internal Testing Website 

[dev.clubs.iiit.ac.in](https://dev.clubs.iiit.ac.in/)

(Works only on internal IIITH network).

## Architecture

![Architecture](/profile/cc-arch.png)

## Repository Structure

![Maintenance](https://img.shields.io/maintenance/yes/2025)

- [Web Client (Frontend)](https://github.com/Clubs-Council-IIITH/web)

    ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/web)
    [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/web)](https://libraries.io/github/Clubs-Council-IIITH/web)

    ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/web?style=plastic)

- [MicroServices (Backend) + Nginx](https://github.com/Clubs-Council-IIITH/services)

    ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/services)
    [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/services)](https://libraries.io/github/Clubs-Council-IIITH/services)

    ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/services?style=plastic)

    - [Authentication Service](https://github.com/Clubs-Council-IIITH/auth)

        <!-- ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/auth)
        [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/auth)](https://libraries.io/github/Clubs-Council-IIITH/auth)

        ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/auth?style=plastic) -->
    
    - [Development Authentication Service](https://github.com/Clubs-Council-IIITH/auth-dev)

        <!-- ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/auth-dev)
        [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/auth-dev)](https://libraries.io/github/Clubs-Council-IIITH/auth-dev)

        ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/auth-dev?style=plastic) 
        -->
    
    - [Files Service](https://github.com/Clubs-Council-IIITH/files)

        <!-- ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/files)
        [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/files)](https://libraries.io/github/Clubs-Council-IIITH/files)

        ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/files?style=plastic) -->
    
    - [Clubs Service](https://github.com/Clubs-Council-IIITH/clubs)

        ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/clubs)
        [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/clubs)](https://libraries.io/github/Clubs-Council-IIITH/clubs)

        ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/clubs?style=plastic)

    - [Members Service](https://github.com/Clubs-Council-IIITH/members)

        ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/members)
        [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/members)](https://libraries.io/github/Clubs-Council-IIITH/members)

        ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/members?style=plastic)
    
    - [Events Service](https://github.com/Clubs-Council-IIITH/events)

        ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/events)
        [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/events)](https://libraries.io/github/Clubs-Council-IIITH/events)

        ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/events?style=plastic)

    - [Users Service](https://github.com/Clubs-Council-IIITH/users)

        ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/users)
        [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/users)](https://libraries.io/github/Clubs-Council-IIITH/users)

        ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/users?style=plastic)
    
    - [Interfaces Service](https://github.com/Clubs-Council-IIITH/interfaces)

        ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/interfaces)
        [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/interfaces)](https://libraries.io/github/Clubs-Council-IIITH/interfaces)

        ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/interfaces?style=plastic)

- [Gateway Service (Microservices)](https://github.com/Clubs-Council-IIITH/gateway)

    ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/gateway)
    [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/gateway)](https://libraries.io/github/Clubs-Council-IIITH/gateway)

    ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/gateway?style=plastic)

    - [~Composer Service~](https://github.com/Clubs-Council-IIITH/composer) _(Deprecated & merged into gateway service itself & in microservices)_

        <!-- ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/composer)
        <> [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/composer)](https://libraries.io/github/Clubs-Council-IIITH/composer) -->

        <!-- ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/composer?style=plastic) -->

- [~Feeder Service Config~](https://github.com/Clubs-Council-IIITH/feeder) _(Deprecated)_

    <!--![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/feeder) -->
    <!-- [![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/Clubs-Council-IIITH/feeder)](https://libraries.io/github/Clubs-Council-IIITH/feeder) -->

    <!--![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/feeder?style=plastic) -->

- [Reverse Proxy Server Config](https://github.com/Clubs-Council-IIITH/reverse-proxy)

    ![GitHub last commit](https://img.shields.io/github/last-commit/Clubs-Council-IIITH/reverse-proxy)

    ![GitHub language count](https://img.shields.io/github/languages/count/Clubs-Council-IIITH/reverse-proxy?style=plastic)
