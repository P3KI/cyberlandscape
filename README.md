# cyberlandscape
Graph data showing relationships between entities in the cyber-political landscape

## Node Attribute Fields

* "name.full" (string) full name of entity
* "name.short" (string) most common shortening of entity's name
* "name.synonym" (string) alternative names the entity might be known under
* "description" (string)
* "url" (string) their main website
* "tasks" (string) list of tasks assigned to the entity
* "level" (string) municipal, county, state, federation, transnational, international
* "org" (string) none, bureau, agency, military, company, association
* "jurisdiction" (string) what (country's?) laws does the entity abide to?
* "employees.total" (long) how many are working there?
* "employees.cyber" (long) how many are working on cyber/IT topics?
* "employees.overhead" (long) how many are there just to keep the show running?
* "founded" (string) ISO-date the entity was founded
* "budget" (long" latest known funding in EUR equivalents
* "publication" (string) list of publication type and recurrence. TODO: define separate type for this?
* "state" (string) none or state the entity is assigned to.

## Edge Attribute Fields
* "oversight.tech" (string) fachaufsicht
* "oversight.legal" (string) rechtsaufsicht
* "directs" (string) weisungsbefugnis ggü...
* "member" (string) mitglied in/bei...
* "shareholder" (float) gesellschafter von... / data: [0,0 1,0] relative number of shares controlled 
* "complements" (string) ergänzt...
* "communicate" (string) tauscht sich aus mit...
* "provides" (string) stellt (zb. präsidenten, ...)...
* "finances" (string) finanziert...
* "educates" (string) bildet aus...
* "cooperates" (string) kooperiert...
* "operates" (string) betreibt...
