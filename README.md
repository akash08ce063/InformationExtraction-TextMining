InformationExtraction-TextMining
================================

 Information Extraction (IE) system for entities and relations in the university domain

Named Entity Detection ---

System can detect the following named entities
University Names (“Concordia University”, “Freie Universit¨at Berlin” or “Ecole Polytechnique”)
, University Person
, University Positions ("Dean","President","Undergraduate Program Director","Assistant Professor")
,Orgranizational Units (e.g., “Department of Computer Science and Software Engineering”,“Faculty of Arts and Science”.)


Coreference Resolution ---

Using GATE’s PRs for nominal and pronominal
coreference resolution and few customized JAPE rules, identify all the diﬀerent mentions of the entities detected above, so that you later
export only one entity for the diﬀerent mentions. E.g., “Mr. Shepard” and “Alan Shepard” would be
recognized as a single entity, and you would later only export one, not two Persons


Relation Extraction ---

Based on the NEs detected above, ﬁnd the relations between a Person and its
Position, and between the unit or university the person works for. For example, from the newspaper
headline "Abrupt exit for Concordia President Woodworths" you would be able to detect (1) a University
(Concordia), a Position (president), a Person (Woodsworth), and infer that 


