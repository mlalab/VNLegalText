# VNLegalText
A Vietnamese legal documents dataset for reference and relation extraction task.

This is an annotated dataset of 5,031 pre-processed Vietnamese legal documents with two labels on reference entities and relations. Assume that we are considering a legal document. A reference entity is a name (or a reference) of a legal document, which is mentioned in the considered legal document. A reference relation is a relation between a reference entity and the considered legal document. Raw data is collected from the Vietnamese Centre Database on Legal Documents (at: http://vbpl.vn) focusing on laws, decrees, and circulars, which are the most popular in the Vietnamese legal system.

### 1)	Statistical information of reference types
-	There are 9 reference types: Constitution, Code, Law, Decree, Circular, Joint Circular, Decision, Ordinance, and Resolution. 
-	Totally, we have 61,446 references belonging to 9 types: Constitution (103), Code (960), Law (21,157), Decree (22,917), Circular (7,033), Joint Circular (424), Decision (4,036), Ordinance (3,926), and Resolution (890). 

### 2)	Statistical information of relation types
-	There are 7 relation types: Is pursuant to, Refers, Expires, Supersedes, Amends or Supplements, Guides, and No relationship.
-	References have one of the following 7 types of relations: Is pursuant to (18,540), Refers (27,783), Expires (1,618), Supersedes (1,765), Amends or Supplements (1,203), Guides (320), and No Relationship (10,217).

