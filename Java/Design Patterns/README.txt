SOFTWARE DESIGN PATTERNS 
————————————————————————


1. ADAPTER DESIGN PATTERN  


2. FACADE DESIGN PATTERN
THE FACADE PATTERN MAKES A COMPLEX INTERFACE EASIER TO USE, USING A FACADE CLASS. THE FACADE PATTERN PROVIDES A UNIFIED INTERFACE TO A SET OF INTERFACE IN A SUBSYSTEM. FACADE DEFINES A HIGHER-LEVEL INTERFACE THAT MAKES THE SUBSYSTEM EASIER TO USE.

3. COMPOSITE DESIGN PATTERN
THE COMPOSITE PATTERN ALLOWS YOU TO COMPOSE OBJECTS INTO A TREE STRUCTURE TO REPRESENT THE PART-WHOLE HIERARCHY WHICH MEANS YOU CAN CREATE A TREE OF OBJECTS THAT IS MADE OF DIFFERENT PARTS, BUT THAT CAN BE TREATED AS A WHOLE ONE BIG THING. COMPOSITE LETS CLIENTS TO TREAT INDIVIDUAL OBJECTS AND COMPOSITIONS OF OBJECTS UNIFORMLY, THAT’S THE INTENT OF THE COMPOSITE PATTERN.

4. BRIDGE DESIGN PATTERN
THE BRIDGE PATTERN’S INTENT IS TO DECOUPLE AN ABSTRACTION FROM ITS IMPLEMENTATION SO THAT THE TWO CAN VARY INDEPENDENTLY. IT PUTS THE ABSTRACTION AND IMPLEMENTATION INTO TWO DIFFERENT CLASS HIERARCHIES SO THAT BOTH CAN BE EXTEND INDEPENDENTLY.

5. SINGLETON DESIGN PATTERN
THE SINGLETON PATTERN IS USED WHEN THERE MUST BE EXACTLY ONE INSTANCE OF A CLASS, AND IT MUST BE ACCESSIBLE TO CLIENTS FROM A WELL-KNOWN ACCESS POINT OR WHEN THE SOLE INSTANCE SHOULD BE EXTENSIBLE BY SUB-CLASSING, AND CLIENTS SHOULD BE ABLE TO USE AN EXTENDED INSTANCE WITHOUT MODIFYING THEIR CODE.

6. OBSERVER DESIGN PATTERN
THE OBSERVER PATTERN IS A KIND OF BEHAVIOR PATTERN WHICH IS CONCERNED WITH THE ASSIGNMENT OF RESPONSIBILITIES BETWEEN OBJECTS. IT SHOULD BE USED WHEN AN ABSTRACTION HAS TWO ASPECTS, ONE DEPENDENT ON THE OTHER, WHEN A CHANGE TO ONE OBJECT REQUIRES CHANGING OTHERS, AND YOU DON’T KNOW HOW MANY OBJECTS NEED TO BE CHANGED OR WHEN AN OBJECT SHOULD BE ABLE TO NOTIFY OTHER OBJECTS WITHOUT MAKING ASSUMPTIONS ABOUT WHO THESE OBJECTS ARE. IN OTHER WORDS, YOU DON’T WANT THESE OBJECTS TIGHTLY COUPLED.

7. MEDIATOR DESIGN PATTERN
THE MEDIATOR PATTERN DEFINES AN OBJECT THAT ENCAPSULATES HOW A SET OF OBJECTS INTERACT. MEDIATOR PROMOTES LOOSE COUPLING BY KEEPING OBJECTS FROM REFERRING TO EACH OTHER EXPLICITLY, AND IT LETS YOU VARY THEIR INTERACTION INDEPENDENTLY. RATHER THAN INTERACTING DIRECTLY WITH EACH OTHER, OBJECTS ASK THE MEDIATOR TO INTERACT ON THEIR BEHALF WHICH RESULTS IN REUSABILITY AND LOOSE COUPLING. YOU WILL LEARN HOW AND WHEN THE MEDIATOR DESIGN PATTERN SHOULD BE USED AND HOW TO STRUCTURE YOUR CODE IN ORDER TO IMPLEMENT IT.

8. PROXY DESIGN PATTERN
THE PROXY PATTERN PROVIDES A SURROGATE OR PLACEHOLDER FOR ANOTHER OBJECT TO CONTROL ACCESS TO IT. IT COMES UP WITH MANY DIFFERENT VARIATIONS. SOME OF THE IMPORTANT VARIATIONS ARE, REMOTE PROXY, VIRTUAL PROXY, AND PROTECTION PROXY. IN THIS LESSON, WE WILL KNOW MORE ABOUT THESE VARIATIONS AND WE WILL IMPLEMENT EACH OF THEM IN JAVA. BUT BEFORE WE DO THAT, LET’S GET TO KNOW MORE ABOUT THE PROXY PATTERN IN GENERAL. YOU WILL LEARN HOW AND WHEN THE PROXY DESIGN PATTERN SHOULD BE USED AND HOW TO STRUCTURE YOUR CODE IN ORDER TO IMPLEMENT IT.

9. CHAIN OF RESPONSIBILITY DESIGN PATTERN
THE CHAIN OF RESPONSIBILITY PATTERN IS A BEHAVIOR PATTERN IN WHICH A GROUP OF OBJECTS IS CHAINED TOGETHER IN A SEQUENCE AND A RESPONSIBILITY (A REQUEST) IS PROVIDED IN ORDER TO BE HANDLED BY THE GROUP. IF AN OBJECT IN THE GROUP CAN PROCESS THE PARTICULAR REQUEST, IT DOES SO AND RETURNS THE CORRESPONDING RESPONSE. OTHERWISE, IT FORWARDS THE REQUEST TO THE SUBSEQUENT OBJECT IN THE GROUP.

10. FLYWEIGHT DESIGN PATTERN
THE FLYWEIGHT PATTERN IS DESIGNED TO CONTROL OBJECT CREATION WHERE OBJECTS IN AN APPLICATION HAVE GREAT SIMILARITIES AND ARE OF A SIMILAR KIND, AND PROVIDES YOU WITH A BASIC CACHING MECHANISM. IT ALLOWS YOU TO CREATE ONE OBJECT PER TYPE (THE TYPE HERE DIFFERS BY A PROPERTY OF THAT OBJECT), AND IF YOU ASK FOR AN OBJECT WITH THE SAME PROPERTY (ALREADY CREATED), IT WILL RETURN YOU THE SAME OBJECT INSTEAD OF CREATING A NEW ONE.

11. BUILDER DESIGN PATTERN
THE INTENT OF THE BUILDER PATTERN IS TO SEPARATE THE CONSTRUCTION OF A COMPLEX OBJECT FROM ITS REPRESENTATION, SO THAT THE SAME CONSTRUCTION PROCESS CAN CREATE DIFFERENT REPRESENTATIONS. THIS TYPE OF SEPARATION REDUCES THE OBJECT SIZE. THE DESIGN TURNS OUT TO BE MORE MODULAR WITH EACH IMPLEMENTATION CONTAINED IN A DIFFERENT BUILDER OBJECT. ADDING A NEW IMPLEMENTATION (I.E., ADDING A NEW BUILDER) BECOMES EASIER.

12. FACTORY DESIGN PATTERN
THE FACTORY METHOD PATTERN GIVES US A WAY TO ENCAPSULATE THE INSTANTIATIONS OF CONCRETE TYPES. THE FACTORY METHOD PATTERN ENCAPSULATES THE FUNCTIONALITY REQUIRED TO SELECT AND INSTANTIATE AN APPROPRIATE CLASS, INSIDE A DESIGNATED METHOD REFERRED TO AS A FACTORY METHOD. THE FACTORY METHOD SELECTS AN APPROPRIATE CLASS FROM A CLASS HIERARCHY BASED ON THE APPLICATION CONTEXT AND OTHER INFLUENCING FACTORS. IT THEN INSTANTIATES THE SELECTED CLASS AND RETURNS IT AS AN INSTANCE OF THE PARENT CLASS TYPE.

13. ABSTRACT FACTORY DESIGN PATTERN
THE ABSTRACT FACTORY (A.K.A. KIT) IS A DESIGN PATTERN WHICH PROVIDES AN INTERFACE FOR CREATING FAMILIES OF RELATED OR DEPENDENT OBJECTS WITHOUT SPECIFYING THEIR CONCRETE CLASSES. THE ABSTRACT FACTORY PATTERN TAKES THE CONCEPT OF THE FACTORY METHOD PATTERN TO THE NEXT LEVEL. AN ABSTRACT FACTORY IS A CLASS THAT PROVIDES AN INTERFACE TO PRODUCE A FAMILY OF OBJECTS.

14. PROTOTYPE DESIGN PATTERN
THE PROTOTYPE DESIGN PATTERN IS USED TO SPECIFY THE KINDS OF OBJECTS TO CREATE USING A PROTOTYPICAL INSTANCE, AND CREATE NEW OBJECTS BY COPYING THIS PROTOTYPE. THE CONCEPT IS TO COPY AN EXISTING OBJECT RATHER THAN CREATING A NEW INSTANCE FROM SCRATCH, SOMETHING THAT MAY INCLUDE COSTLY OPERATIONS. THE EXISTING OBJECT ACTS AS A PROTOTYPE AND CONTAINS THE STATE OF THE OBJECT.

15. MEMENTO DESIGN PATTERN
SOMETIMES IT’S NECESSARY TO RECORD THE INTERNAL STATE OF AN OBJECT. THIS IS REQUIRED WHEN IMPLEMENTING CHECKPOINTS AND “UNDO” MECHANISMS THAT LET USERS BACK OUT OF TENTATIVE OPERATIONS OR RECOVER FROM ERRORS. YOU MUST SAVE STATE INFORMATION SOMEWHERE, SO THAT YOU CAN RESTORE OBJECTS TO THEIR PREVIOUS CONDITIONS. BUT OBJECTS NORMALLY ENCAPSULATE SOME OR ALL OF THEIR STATE, MAKING IT INACCESSIBLE TO OTHER OBJECTS AND IMPOSSIBLE TO SAVE EXTERNALLY. EXPOSING THIS STATE WOULD VIOLATE ENCAPSULATION, WHICH CAN COMPROMISE THE APPLICATION’S RELIABILITY AND EXTENSIBILITY. THE MEMENTO PATTERN CAN BE USED TO ACCOMPLISH THIS WITHOUT EXPOSING THE OBJECT’S INTERNAL STRUCTURE.

16. TEMPLETE DESIGN PATTERN
THE TEMPLATE DESIGN PATTERN IS A BEHAVIOR PATTERN AND, AS THE NAME SUGGESTS, IT PROVIDES A TEMPLATE OR A STRUCTURE OF AN ALGORITHM WHICH IS USED BY USERS. A USER PROVIDES ITS OWN IMPLEMENTATION WITHOUT CHANGING THE ALGORITHM’S STRUCTURE. THE TEMPLATE PATTERN DEFINES THE SKELETON OF AN ALGORITHM IN AN OPERATION, DEFERRING SOME STEPS TO SUBCLASSES. TEMPLATE METHOD LETS SUBCLASSES TO REDEFINE CERTAIN STEPS OF AN ALGORITHM WITHOUT CHANGING THE ALGORITHM’S STRUCTURE.

17. STATE DESIGN PATTERN
THE STATE DESIGN PATTERN ALLOWS AN OBJECT TO ALTER ITS BEHAVIOR WHEN ITS INTERNAL STATE CHANGES. THE OBJECT WILL APPEAR TO CHANGE ITS CLASS. THE STATE OF AN OBJECT CAN BE DEFINED AS ITS EXACT CONDITION AT ANY GIVEN POINT OF TIME, DEPENDING ON THE VALUES OF ITS PROPERTIES OR ATTRIBUTES. THE SET OF METHODS IMPLEMENTED BY A CLASS CONSTITUTES THE BEHAVIOR OF ITS INSTANCES. WHENEVER THERE IS A CHANGE IN THE VALUES OF ITS ATTRIBUTES, WE SAY THAT THE STATE OF AN OBJECT HAS CHANGED.

18. STRATEGY DESIGN PATTERN
THE STRATEGY DESIGN PATTERN SEEMS TO BE THE SIMPLEST OF ALL DESIGN PATTERNS, YET IT PROVIDES GREAT FLEXIBILITY TO YOUR CODE. THIS PATTERN IS USED ALMOST EVERYWHERE, EVEN IN CONJUNCTION WITH THE OTHER DESIGN PATTERNS. THE STRATEGY DESIGN PATTERN DEFINES A FAMILY OF ALGORITHMS, ENCAPSULATING EACH ONE, AND MAKING THEM INTERCHANGEABLE. STRATEGY LETS THE ALGORITHM VARY INDEPENDENTLY FROM THE CLIENTS THAT USE IT.

19. COMMAND DESIGN PATTERN
THE COMMAND DESIGN PATTERN IS A BEHAVIORAL DESIGN PATTERN AND HELPS TO DECOUPLES THE INVOKER FROM THE RECEIVER OF A REQUEST. THE INTENT OF THE COMMAND DESIGN PATTERN IS TO ENCAPSULATE A REQUEST AS AN OBJECT, THEREBY LETTING THE DEVELOPER TO PARAMETERIZE CLIENTS WITH DIFFERENT REQUESTS, QUEUE OR LOG REQUESTS, AND SUPPORT UNDOABLE OPERATIONS.

20. INTERPRETER DESIGN PATTERN
THE INTERPRETER DESIGN PATTERN IS A HEAVY-DUTY PATTERN. IT’S ALL ABOUT PUTTING TOGETHER YOUR OWN PROGRAMMING LANGUAGE, OR HANDLING AN EXISTING ONE, BY CREATING AN INTERPRETER FOR THAT LANGUAGE. GIVEN A LANGUAGE, WE CAN DEFINE A REPRESENTATION FOR ITS GRAMMAR ALONG WITH AN INTERPRETER THAT USES THE REPRESENTATION TO INTERPRET SENTENCES IN THE LANGUAGE.

21. DECORATOR DESIGN PATTERN
THE INTENT OF THE DECORATOR DESIGN PATTERN IS TO ATTACH ADDITIONAL RESPONSIBILITIES TO AN OBJECT DYNAMICALLY. DECORATORS PROVIDE A FLEXIBLE ALTERNATIVE TO SUB-CLASSING FOR EXTENDING FUNCTIONALITY. THE PATTERN IS USED TO EXTEND THE FUNCTIONALITY OF AN OBJECT DYNAMICALLY WITHOUT HAVING TO CHANGE THE ORIGINAL CLASS SOURCE OR USING INHERITANCE. THIS IS ACCOMPLISHED BY CREATING AN OBJECT WRAPPER REFERRED TO AS A DECORATOR AROUND THE ACTUAL OBJECT.

22. ITERATOR DESIGN PATTERN
THE INTENT OF THE ITERATOR DESIGN PATTERN IS TO PROVIDE A WAY TO ACCESS THE ELEMENTS OF AN AGGREGATE OBJECT SEQUENTIALLY WITHOUT EXPOSING ITS UNDERLYING REPRESENTATION. HE ITERATOR PATTERN ALLOWS A CLIENT OBJECT TO ACCESS THE CONTENTS OF A CONTAINER IN A SEQUENTIAL MANNER, WITHOUT HAVING ANY KNOWLEDGE ABOUT THE INTERNAL REPRESENTATION OF ITS CONTENTS.

23. VISITOR DESIGN PATTERN
THE VISITOR DESIGN PATTERN PROVIDES YOU WITH A WAY TO ADD NEW OPERATIONS ON THE OBJECTS WITHOUT CHANGING THE CLASSES OF THE ELEMENTS, ESPECIALLY WHEN THE OPERATIONS CHANGE QUITE OFTEN. THE INTENT OF THE VISITOR DESIGN PATTERN IS TO REPRESENT AN OPERATION TO BE PERFORMED ON THE ELEMENTS OF AN OBJECT STRUCTURE. VISITOR LETS YOU DEFINE A NEW OPERATION WITHOUT CHANGING THE CLASSES OF THE ELEMENTS ON WHICH IT OPERATES.

24. COLLECTIONS DESIGN PATTERN

25. COMBINED DESIGN PATTERN

26. COMBINING DESIGN PATTERN

27. DUCKS DESIGN PATTERN

28. ITERENUM DESIGN PATTERN

29. TEMPLATEMETHOD DESIGN PATTERN








SOFTWARE DESIGN AND ARCHITECTURE COURSES 
----------------------------------------


BASICS OF SOFTWARE ARCHITECTURE & DESIGN PATTERNS IN JAVA - UDEMY 

EXPERIENCE DESIGN PATTERNS IN JAVA - UDEMY 

JAVA DESIGN PATTERNS AND ARCHITECTURE - UDEMY/ JOHN PURCELL 

FROM 0 TO 1: DESIGN PATTERNS - 24 THAT MATTER IN JAVA - UDEMY/ LOONY CRON  

BYTE SIZE CHUNKS : JAVA MODEL-VIEW-CONTROLLER (MVC) - UDEMY/ LOONY CRON  

SOFTWARE ARCHITECTURE & DESIGN - UDACITY

SOFTWARE DEVELOPMENT PROCESS - UDACITY

OBJECT ORIENTED TUTS - DEREK BANAS 

DESIGN PATTERNS - DEREK BANAS 

DZONE DESIGN PATTERN <HTTPS://DZONE.COM/REFCARDZ/DESIGN-PATTERNS>

DZONE DOMAIN-DRIVEN DESIGN <HTTPS://DZONE.COM/REFCARDZ/GETTING-STARTED-DOMAIN-DRIVEN>