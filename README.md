# MockFlow Wireframe Guide

This is the wireframe guide for the ICT2201 Project done by Team P5-4. This guide describes how to use the MockFlow application to
navigate through our wireframe, to touch on every features that it has. Do note that MockFlow does not allow textbox input for 
prototyping, so the wireframes will assume that all textboxes have valid inputs.



## Flows and Features

Our wireframe possesses 3 different flows for the 3 different type of users that uses our web application which are, staff, manager
, and IT administrators. The functionalities of each of the user will be stated here alongside which webpage contains it:

#### Staff:
- Login page
    - Logging into staff account
- Staff landing page
    - View his/her overall workload of the month
    - View his/her current week job assignment
- Job assignment rejection page
    - Reject job assigned
- Availability management page
    - Add/Edit availabilities for the week
- Indicate preference page
    - Indicate/Edit job preference for the week

#### Manager:
- Login page
    - Logging into manager account
- Manager landing page
    - View top 3 staff with lowest workload
    - View workload assigned to staff for the week
    - All staff over 40 hours of jobs will be highlighted
- Job allocation page
    - Add/Edit/Delete weekly allocation of job to staff
    - View staff availability for the job
    - View location the staff is allocated to
    - View staff job preference
    - View availability of staff weekly

#### IT admin:
- Login page
    - Logging into IT admin account
- User management page
    - Adding of new staff or manager accounts
    - Editing/Removing existing staff or manager accounts
## User Guide

This user guide will lead you through all the flows and features stated in the above section. Once you have logged into
the MockFlow account, access the wireframe clicking on the button at the top right of the page as shown below.

![alt text](https://i.gyazo.com/8fbe29ea863c77e4d9057ca8a97a0550.png)

Next, go to 'M2' > 'ICT2203 Wireframe' to access our wireframe. On the pages tab on the left side bar, you can see three folders.
Each of the three folders contain the wireframe flow for staff, manager, and IT admin.

![alt text](https://i.gyazo.com/8c7d5adc0ce5d2d50a728841eb3d84c4.png)

### Staff's Flow

#### Login page

To go through the staff's flow, expand the 'Staff Demo' folder, select the 'Login Page - Staff', and click on the 'Review' button
as shown in  the top right of the image below.

![alt text](https://i.gyazo.com/220fa0d98f4fb8a0e3be0e2e79094995.png)

You should be at the login page now, and you can click on the Login button to log into a staff account, and be redirected to the 
staff landing page.

#### Staff landing page

The staff landing page consists of two tables that shows the staff's overall workload of the month, as well as his/her current
week job assignment.

#### Job assignment rejection page

To reject a job assignment, please click the red 'X' button under the Reject column for the job assignment for City Hall, as shown below.

![alt text](https://i.gyazo.com/904ad6308e35c2b5cce487c5a8ff903d.png)

You will then be redirected to the job assignment rejection page for the job assignment that you have selected, which in this case
is City Hall's first shift on 17-10-22.

For this wireframe prototyping, just click on the Submit button as the wireframe will assume the 
staff has entered a valid reason.

A success message will then be displayed to inform the staff that the job has been successfully rejected as shown below. Click on the Exit
button to go back to the landing page.

#### Availability management page

To access the availability manage page, expand the navigation bar on the left of any page and click on the 'Add/Edit Availabilities'
button located on the navigation bar to be redirected to the page.

To set availability, simply use the dropdown box on each day to indicate whether the staff is 'Available' or 'Unavailable'. But for
the purpose of speeding up the prototyping, simply set the status of 10-10-22 to Available as shown in the image, in order to automatically set all the other dates.
Once all the dates have been set, the staff can click the Confirm button to submit the his/her availabilities.

![alt text](https://i.gyazo.com/75f5b299a27a5b50f70977de119a54e1.png)

If successful, a success message will be displayed. Click on the Exit button on the success message to be redirected to the page where
the staff can see all his/her availabilities. If the staff wishes to edit, they can click on the yellow pencil button on the bottom right
to go back to the editing page.

If not all dates are set, an error message will be shown to the staff.

#### Indicate preference page

To access the indicate preference page, expand the navigation bar on the left of any page and click on the 'Indicate Preference'
button located on the navigation bar to be redirected to the page.

To set job preference, simply use the dropdown box on each date to indicate which shift or location they would like to work at. But for
the purpose of speeding up the prototyping, simply set the shift of 17-10-22 to 'Shift 1' as shown in the image below, in order to automatically
set all the other preferences. Once preferences have been set, click on the green tick button at the bottom right to submit.

![alt text](https://i.gyazo.com/e655782d7338eacf2b3cca324e15b6de.png)

The staff will then be redirected to the page where the staff can see all his/her preferences. If the staff wishes to edit, they can click on the yellow pencil button on the bottom right
to go back to the editing page.

In the editing page, the staff can choose to remove preference if they wish to by clicking on the red 'X' remove button. For this prototyping session,
click on the remove button for the row of date '23-10-22' as shown below, to delete the job preference for that day. A
confirmation message will be displayed, click on 'Yes' to delete the job preference.

![alt text](https://i.gyazo.com/f35361e18db48b5dbdebdd2906c0ffe4.png)

### Manager's Flow

#### Login page

Next, to go through the manager's flow, expand the 'Manager Demo' folder, select the 'Login Page - Manager', and click on the 'Review' button like before.

You should be at the login page now, and you can click on the Login button to log into a manager account, and be redirected to the 
manager landing page.

#### Manager landing page

The staff landing page consists of two tables that shows the top 3 staff with lowest workload, and the workload of all the staff members.
All the staff with over 40 hours of workload allocated to them are also highlighted in red.

#### Job allocation page

To go to the job allocation page, click on the 'Allocate Job' button on the left side navigation bar of the landing page to be
redirected to the job allocation page.

In the job allocation page, click on the green '+' button on a job branch to allocate a staff to the job. For this prototyping session,
click on the Add button for the job branch Orchard as shown in the image below.

![alt text](https://i.gyazo.com/ca8234ffad31b3a0e509c4bafc8ec884.png)

To add a staff to the job, use the dropdown box to select a time slot and the staff to allocate to the selected time. For this prototyping session,
select the time as '0900-1800' and the staff as 'John', and then select the time as '1200-2100' and the staff as 'Peter'. The page should be 
as shown below.

Click on the Add button again to confirm the allocation of the staffs to jobs. If the green Add button turns into a yellow Edit button, it means that the specific
job has been allocated.

Now, click on the yellow Edit button to edit the job allocation as shown below. Dropdown boxes should appear to allow you to change
the job allocation to different staffs. Change the allocation of job from 'John' to 'Chris'.
Click on the green Add button again to complete the editing.

![alt text](https://i.gyazo.com/7c38b80545a45fa08c90109c404acbac.png)

Lastly, to remove an allocated job, simply click the red '-' remove button on the job. For this prototyping session, click the remove button
on the job you have just created as shown below.

![alt text](https://i.gyazo.com/e9aa9b25c18fb332198cfb321ae04d85.png)

### IT Admin's Flow

#### Login page

Next, to go through the manager's flow, expand the 'IT Admin Demo' folder, select the 'Login Page - IT Admin', and click on the 'Review' button like before.

You should be at the login page now, and you can click on the Login button to log into a IT Admin account, and be redirected to the 
IT Admin landing page.

#### User management page

Now you should be at the landing page. Click on the 'Manage Users' button either on the landing page or on the left side navigation
bar to be redirected to the user management page.

To add a user, click the green '+' button on the bottom of the page as shown in the figure below to display the form to add a new user.

![alt text](https://i.gyazo.com/12f2c8a196c510e810fd1771037760a4.png)

Normally, to add a new user, the IT admin has to make sure that all the input fields are filled up and it fits the requirements.
However, this prototyping session assumes that the input fields have already been filled in with valid input. Simply click on the blue tick
button at the bottom of the form to create a new user. A 'User has been successfully created' message should show, and click on the green arrow
to return to the user management page.

Next, to edit the details of a user, click on the yellow 'Edit' button on the row of the user 'John Lee' as shown below to display the form.

![alt text](https://i.gyazo.com/71c76f5105cb6498a89d645e6c9e5b97.png)

Similarly, this prototyping session assumes that the input fields have already been filled in with valid input, so simply click on the blue
button at the bottom of the form to complete editing the user. A 'User details has been successfully edited' message should show.

Next, to delete a user, click on the 'X' button on the row of the user 'Kenneth Lim' as shown below. A confirmation message should show up, click
on 'Confirm' to delete the user. A 'User has been successfully removed from the system' message should show up.

![alt text](https://i.gyazo.com/e2ab94370d04395dfdbaf37f6cf4e9e4.png)
