Download Link: https://assignmentchef.com/product/solved-cmput-291-assignment-1-concepts-of-database-design-using-er-model
<br>
<table width="988">

 <tbody>

  <tr>

   <td width="988">The goal of this assignment is to reinforce the concepts of database design using Entity-Relationship (ER) model and mapping an ER model into a relational model. This assignment has two parts.Part I – ModelingYou are building a database for Service Alberta to maintain data for various services offered. Given the database specification below, your job is to turn the specification into an ER diagram. You are using dia (see <a href="https://www.gnome.org/projects/dia/">documentation for dia</a><a href="https://www.gnome.org/projects/dia/">)</a> to draw your ER diagram. Your notation must be consistent with the notation used in our lecture notes. You can use all constructs and notations discussed in our lecture notes and nothing else (i.e., even notations used in the textbook but not in our lectures cannot be used).You will be working in groups of 2-3; group members must be all registered in the course but they may not be all in the same lecture or lab section. Your ER diagram should capture all the information and constraints in the specification, but at the same time be minimal, meaning redundant entities, relationships, attributes and constraints should be avoided.Database SpecificationThe database keeps detailed information about vehicles, drivers, vital records, etc.Each person (known to Service Alberta) has a first name, a last name, a birth date, a birth place, an address and a phone number. You can assume a subset of the attributes (e.g., first name, last name and birth date) is unique. For each driver, eyes color and hair color are also recorded. Each traffic officer also has a city where the officer operates.Records of births and marriages in the province are maintained. For each birth in Alberta, in addition to the personal details of the person born (as listed above), there is a unique registration number, a registration date, a registration place, a gender at birth, a mother and a father. A birth may be registered without a father but always has a mother. Each marriage in the province is also recorded, and it has a unique registration number, a registration date, a registration place, and the details of the partner persons, referred to as Partner 1 and Partner 2.Drivers can obtain drivers’ licenses. Each driver’s license has a unique license number, a date issued, an expiry date and a license class. Each driver’s license must be issued to a driver. There are a set of license classes, and each class has a unique id and a description.Each vehicle has a unique VIN, a make, a model, a year, and a color. Vehicles are registered before they can be operated. Each vehicle registration in Alberta has a unique registration number, a registration date, an expiry date, an Alberta plate and a driver registered as the owner. A vehicle can have multiple registrations and a driver can also have multiple registrations.Registered vehicles can be given tickets. Each ticket given to a registered vehicle has a unique ticket number, an offence date, the offence cited, a fine dollar amount, and sometimes a traffic officer issuing the ticket. Drivers can have demerit point notices in their records. Each notice has a date, a description and the number of demerit points.Part II – MappingMap the following ER diagram into relational tables using the rules discussed in class. Give the complete CREATE TABLE commands for each necessary table including attribute names, their domains/types and all possible constraints. Use your common sense to choose a domain for each attribute.</td>

  </tr>

 </tbody>

</table>

(The dia file is also <a href="https://eclass.srv.ualberta.ca/pluginfile.php/5149331/mod_page/content/37/a1p2.dia?time=1568316855673">here</a><a href="https://eclass.srv.ualberta.ca/pluginfile.php/5149331/mod_page/content/37/a1p2.dia?time=1568316855673">)</a>

<h1>Deliverables</h1>

Submit a single tar file for your group named a1.tgz. The submitted tar file is expected to have the following pieces:

<ol>

 <li>A file named CCID-P1.pdf for every group member (replace CCID with the member CCID). This file is the PDF of the ER diagram prepared by the member for Part I. If the group includes, for example, three members, there should be three such files.</li>

 <li>A file named group-P1.pdf. This file is the PDF of the ER diagram prepared by the group for Part I, possibly more comprehensive or accurate than the individually prepared diagrams. Only one group solution is submitted for this part.</li>

 <li>A file named group-P2.txt. This file is a text file that has the group solution for Part II. The solution includes the relations (CREATE TABLE statements) obtained when mapping the given ER-model in Part II to the Relational model. Only one group solution is submitted for this part.</li>

 <li>A file named readme.txt. This is a text file that lists the names and ccids of all group members. This file must also include the names of anyone you collaborated with (as much as it is allowed within the course policy) or a line saying that you did not collaborate with anyone else. A submission without this file or with missing information can lose 5% or more of the total mark. This is also the place to acknowledge the use of any source of information besides the course textbook and/or class notes.</li>

 <li>A file named comments.txt. This is a text file that lists comments made by each member on the ER diagram of another group member. Clearly indicate the ccid of the member commenting and the ccid of the member whose ER diagram is being commented.</li>

 <li>Additional files (e.g., you may have the ER for Part 2 and show in drawing how the elements are grouped to form a relation) may be submitted.</li>

</ol>

Those files should be given proper or meaningful names and you should understand that we cannnot those files will be checked.

<table>

 <tbody>

  <tr>

   <td width="86"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

The tar file can be created under Linux (lab machines) and MacOS using the command

tar -czf a1.tgz   &lt;all-the-files-to-be-included&gt;

where &lt;all-the-files-to-be-included&gt; is replaced with the names of all files you are including in your submission.

Your ER diagrams should be produced with the ‘<a href="https://www.gnome.org/projects/dia/">dia</a>‘ tool available on the lab machines (<a href="http://dia-installer.sourceforge.net/">here is a link to Windows and Mac versions of dia</a>– use it at your own risk) and exported in PDF. You must use the same notation used in the course lectures. If you are making any assumptions in your modeling or mapping, state them clearly in your readme.txt; note that your assumptions cannot violate the specification given here and any possible clarification posted later on top of this page or the course forums.