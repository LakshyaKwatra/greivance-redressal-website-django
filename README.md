# greivance-redressal-website-django
This website has been built for ESD, Department of ITE&C, Govt. of Telangana. This portal is meant to be used by the ESD for the users to register and lodge complaints regarding the MeeSeva facility. Citizens are intimated by an e-mail/SMS when a complaint is resolved.

Django version: 2.0.2.
# Instructions to Run
- Run the following command in the command line in the project directory 
> python manage.py runserver
# User Level Description
There are 5 levels of users:
1. **Citizen**
  - Can login
  - Lodge a complaint
  - Have a user profile with personal details-ability to edit email and phone number and provision check all complaints posted by them

2. **Staff**
  - Citizen permissions
  - Have a dashboard of all complaints to view, resolve amd mark as pending/resolved/spam
  - Sort functionality in dashboard

3. **Manager**
  - Staff permissions
  - Have a dashboard of all complaints logged and resolved/marked as spam with satistics of complaints resolved by staff

4. **Support Staff**
  - Staff permissions
  - Have a separate complaint dashboard to allot complaints to specific staff users

5. **Superuser**
  - All website access and admin page

# User Details
- Superuser:
  - username: testing
  - password: esd@telwap
  - All other users have password: testing123

- Current Users:
  - user1: normal access
  - user2: staff level access
  - user3: manager level access
  - user4: support staff level access
  - testing: superuser
