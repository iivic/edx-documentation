.. _Programs:

################
About Programs
################

Programs are collections of related courses that you make available on your
marketing site.

You add programs and specify the courses that are in each program in the
Django Administration site for your Open edX instance.

The cost for a program is the sum of the cost for each of its courses. You can
change the cost for a program by creating a program offer, which is a discount
on the program price of either a percentage or fixed amount. For more details,
see :ref:`Create Program Offers`.



***************
Create Programs
***************





To add a program, follow these steps.

#. Sign into the Django administration site for the discovery service.

#. In the **Course Metadata** section, select **Programs**.

#. Select **Add Program**.

#. On the **Add Program** page, a UUID is assigned to the new program.

#. Enter the information for the new program. Required fields, for example
   **Title** and **Status** have boldface names.

   Specify the courses that are part of the program by entering course names in
   the **Courses** field. Names of courses that already exist in the discovery
   service are automatically matched as you continue to type.



.. note:: To allow learners to purchase upgrades to the verified track for all
   the courses in the program with one click, select **One click purchase
   enabled**.

#. When you have finished entering information for the program, select one of
   the **Save** options: **Save**, **Save and add another**, or **Save and
   continue editing**.

This procedure completes the course and program structure. To provide "site functionality" for programs, the front end needs to know about the program and the program's cost





.. include:: ../../../../links/links.rst
