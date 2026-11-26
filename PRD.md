# ~Babcock University Student Transportation System [BU-Ride]~
    **Developers**- TetraStack
    **Location**- Babcock University, Ilishan-Remo, Ogun State, Nigeria


## Problem Recognised~
    Students of Babcock University often have problems when it comes to the transport system of the school which is mainly the use of tricycles (Kekes) especially when going to major areas or classes far away from their hall of residence or current location. 

    Students usually run late to their destination due to drivers not going their way or full Kekes passing their current location and it can take long time for them to get a ride which sometimes they have the charter at higher prices cause drivers don't want to go far or that particular student is the only one going to the location such as BUTH, Pioneer Church, EAH etc.
    
    They also complain of regular snubbing from keke drivers who pass along their routes.

    There is also no platform through which students can find available kekes, request transportation, track drivers or connect with other students going in similar directions.


## Project Overview, Vision and Solution to the recognised problem~
    BU-Ride is a mobile transportation platform designed to improve the transportation experience of students within Babcock University.
    It connects students to registered Keke drivers using an automated driver-matching system. It enebles students to request individual rides, create shared rides with other students going in the same direction, or join existing rides with available seats.
    The platform is going to be operating somewhat like UBER but for students in the university containing features such as real-time driver tracking, ride requests, driver verification, fixed price rates, digital payments and trip management.
    The main aim of BU-Ride is to make transportation more accessible, reliable, and convenient for students while helping registered keke drivers connect with passengers more efficiently and in real time.


## Target Audience Based on Research Findings~
    BU-Ride is primarily for Students of Babcock University.
        The Platform is going to be divided into three user parts:
            ~Student Side-
                ~Students who regularly use commercial kekes for 
                transportation.
                ~Students who struggle to find transportation during 
                busy periods etc.
            ~Driver Side-
                ~Commercial keke drivers operating within and around Babcock 
                University.
                ~Drivers interested in receiving ride requests through a digital 
                platform.
                ~Drivers who want to manage their availability and connect with 
                passengers etc.
            ~Admin Side-
                ~Those responsible for verifying drivers, managing user accounts, 
                monitoring activities and handling complaints.


## Platform Features and Functional Requirement~
    ### Student Registration and Authentication Process...
            -Students should be able to create accounts using their Babcock Email 
            address and their phone numbers.
        ### Functional Requirement (Student Side)...
            -Students should be able to provide their full names.
            -Students should be able to register using their Babcock University 
            email addresses.
            -Students should be able to provide active phone numbers.
            -Students should be able to create strong passwords.
            -The system should be able to verify email ownership using OTP and the 
            likes.
            -Phone numbers should be able to be verified using an OTP.
            -Students should be able to be able to log in and log out.
            -Students should be able to be able to reset forgotten passwords.
            -Students should be able to be able to manage their profile 
            information.
    ### Driver Registration and Authentication Process...
            -All Keke drivers must register on the platform before receiving 
            requests.
        ### Information the Platform will Require from the Drivers...
            -Full name.
            -Phone number.
            -Keke registration or plate number.
            -Vehicle details.
            -Profile photograph.
            -Account Details (For In-app payment).
        ### Functional Requirement (Driver Side)...
            -Drivers should be able to submit their information during 
            registration.
            -Unverified drivers should not be allowed to receive ride requests.
            -Drivers should be able to update their profiles.
            -Approved drivers should be able to access the driver dashboard.
            -Pricing and account details should be placed on the dashboard for  students to see.
    ### Admin Side...
        -Administrators should be able to review and verify driver information.
        -They should be able to manage user accounts (all sides of the platform).
        -They should be able to monitor activities real time.
        -They should to able to handle complaints and give feedback.
    ### Overall Management System Requirement for Drivers...
            -Drivers must be able to manage when they are available to receive 
            ride requests.
        ### The platform should permit the following features...
            -Drivers can switch their status to Online or Offline.
            -Online drivers can receive ride requests.
            -Their location can be shared while online and available for rides.
            -Offline drivers must not receive new ride requests.
            -Drivers can schedule the days and hours they intend to work.
            -Drivers can edit or cancel schedules.
            -Scheduled and immediate availability must be differenciated.
        ### Driver-Student Matching Feature...
            -The platform must automatically match students with available 
            drivers using certain factors to match...
                *Student's current location.
                *Student's intended destination.
                *Driver's current location.
                *Number of available seats.
                *Driver's availability status.
                ### Functional Requirements...
                    -Students must be able to enter their pickup and destination 
                    locations.
                    -The system must identify available drivers.
                    -The system must assign the most available driver.
                    -Drivers must receive ride requests.
                    -Drivers must be able to accept or decline requests.
                    -If a driver declines or does not respond within the defined 
                    period, the system must attempt another match.
                    -Students must receive booking status updates.
    ### Booking System...
        -When using the platform, Students should be able to request for 
        transportation.
        ### Functional Requirement...
            -Students must be able to select their pickup location.
            -Students must be able to select their destination.
            -Students must be able to select between exclusive and shared rides.
            -Students must be able to indicate whether they have luggage.
            -The system must display the applicable fare.
            -Students must select a payment method.
            -Students must be able to confirm their requests.
            -Students must receive booking confirmation once a driver accepts.
        ### Types of Booking and their Functionalities offered by the Platform...
            ### *Exclusive Booking...
                -Students should be able to request for a private Keke ride.
                    ### Functional Requirement...
                        -An exclusive ride must be reserved for the requesting 
                        student only.
                        -The driver must proceed directly to the selected 
                        destination.
                        -Additional passengers must not be picked up along the 
                        route.
                        -The system must prevent other students from joining an 
                        exclusive booking.
                        -Students must be able to track their assigned drivers 
                        using real time GPS locator.
            ### *Shared Ride Booking...
                -The platform should allow to students to be able to create and 
                join shared rides
                    ### Functional Requirement when creating ride...
                        -Students select their pickup and destination.
                        -Students create a shared ride request.
                        -Other students going in similar directions can discover 
                        the ride.
                        -Interested students can request to join.
                        -The system displays the number of available seats.
                        -The system coordinates the ride with a suitable driver.
                    ### Functional Requirement when joining ride...
                        -Students can view available shared rides.
                        -Students can view destinations and pickup locations.
                        -Students can view available seats.
                        -Students can view their expected fare.
                        -Students can request to join existing rides.
            ### Vehicle Capacity...
                -The system must prevent bookings beyond the vehicle's passenger 
                limit (4)
    ### Real-Time Location Tracking System...
        -As said earlier, The platform is similar to the UBER ride platform so it 
        is going to have a real-time tracking system to enable students track their 
        ride in real time.
            ### Functional Requirement...
                -Students must be able to see the assigned driver's location on a 
                map.
                -Drivers' locations must update while they are online and on an 
                active trip.
                -Students must be able to track drivers approaching their pickup 
                locations.
                -Students must be able to view estimated arrival times.
                -Students must be able to track their trips.
                -The system must stop sharing trip-related live location when the 
                trip ends.
    ### Pricing System...
        ### Functional Requirement...
            -he standard fare must be ₦200.
            -The fare for a passenger with luggage must be ₦500.
            -The luggage fare must replace not add to the standard fare.
            -Fares must remain fixed regardless of destination within the school.
            -Drivers must not increase platform fares set by Admin.
            -The system must display fares before ride confirmation.
            -The fare must be calculated automatically based on selection type.
    ### Payment System...
        ### Cash Payment System...
            ### Functional Requirement...
                -Students can select cash as their preferred method of payment.
                -Payment is made directly to the driver.
                -Drivers must be able to confirm that cash was recieved in place of 
                in-app payment.
        ### In-App Payment System...
            ### Functional Requirement...
                -Students can pay through selection of bank of choice to the 
                driver's account details displayed.
                -The system must confirm successful transactions.
                -Students must receive digital receipts.
                -Students must be able to view payment history.
                -The system must be able to distinguish successful, pending and 
                failed payments.
                -Duplicate charges must be prevented.

## User Stories
    -Users want to get Keke rides on time
    -Users want to be able to schedule their bookings
    -Users want to be able track their drivers in real time.

# ## MVP
    For the first version:
    It must contain:
    -A Student side
    -A Users side
    -An Admin side 
    -Booking system
    -Matching System to match available drivers with students.
