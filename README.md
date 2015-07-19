# AECHackathon2015

Not really an entry but my experimental work for the AEC Hackathon London 2015 in aid of the Optioneers team.

## IFC Parser

IFC Components are more complex that I am treating them, and I'm sure theres much more than can be done that just a 'parser', but the intention is to provide a JSON/Object representation of a BIM model. The model is used by BIMServer and BIMSurfer (or other renderers) to generate a WebGL scene, for which I think a JSON/Object representation of the model can provide some better implementation between interface and the scene/model.

The intention is to be able to modify the IFC JSON/Object, give it to the BIM server and have some external program render it. Currently, the model is sent from the BIM Server to whatever renders it, and is then visualised in some WebGL renderer - I'm not sure on the specifics of how it interacts but it would be cool if a user can select options for a house (different windows, doors, wall thickness) and be able to generate an IFC collection/BIM Model which can then be rendered by Architects using their own software.

You know what, now that I think of it, I think the BIM Surfer does all this anyway. Who knows, still a cool idea to parse a tree-based object into some JS usable format.
