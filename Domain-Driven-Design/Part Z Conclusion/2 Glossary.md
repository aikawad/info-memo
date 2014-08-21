#Glossary

__AGGREGATE__
> A cluster of associateed object that are treated as a unit for the purpose of data changes. External references are restricted to one member of the AGGREGATE, designated as the root. A set of consistenncy rules applies within the AGGREGATE'S boundaries.


__analysis pattern__
> A group of concepts that represents a common construction in business odeling. It may be relevant to only one domain or may span many domains(Fowler 1997,p. 8)


__ASSERTION__
> A statement of the correct state of  program at some point, independent of how it does it. Typically, an ASSERTION specifies the result of an operation or an invariant of a design element.

__BOUNDED CONTEXT__
> The delimited applicability of a particular model. BOUNDING CONTEXTS gives team members a clear and shared understanding of what has to be consistent and what can develop independently.

__client__
> Aprogram element that is calling the element under design, using its capabilities.

__cohesion__
> Logical agreement and dependence.

__command__
>(a.k.a modifier) An operation that effects some change to the system ( for example, setting a variable). An operation that intentionally creates a side effect.

__CONCEPTUAL CONTOUR__
> An underlying consistency of the domain itself, which, if reflected in a model, can help the design accommodate change more naturally.

__context__
> The setting in which a word or statement appears that determines its meaning. See BOUNDE CONTEXT.

__CONTEXT MAP__
> a representation of the BOUNDED CONTEXTS involved in a project and he actual relationships between them and their models.

__CORE DOMAIN__
> The distinctive part of the model, central to the user's goals, that differentiates the application and makes it valuable.

__declarative design__
> A form of programming in which a precise description of properties actually controls the software. An executable specification.

__deep model__
> An incisive expression of the primary concerns of the domain experts and their most relevant knowledge. A deep model sloughs off superficial aspects of the domain and naive interpretations.

__design pattern__
> A description of communicating objects and classes that are customized to solve a general design problem in a particular context. ( Gamma et al. 1995, p.3)

__distillation__
> A process of separating the components of a mixture to extract the essence in a form that makes it more valuable and useful. In software design, the abstraction of key aspects in a model, or the partitioning of a larger system to bring the CORE DOMAIN to the fore.

__domain__
> A sphere of knowledge, influence, or activity.

__domain expert__
> A member of a softwar project whose field is the domain of the application, rather than software development. Not just any user of the software, the domain expert has deep knowledge of the subject.

__domain layer__
> That portion of the design and implementation responsible for domain logic within a LAYERED ARCHITECTURE. The domain layer is where the software expression of the domain model lives.

__ENTITY__
> An object fundamentally defined not by its attributes, but by a thread of continuity and identity.

__FACTORY__
> A mechanism for encapsulating complex creation logic and abstracting the type of a created object for the sake of a client.

__function__
> An operation that computes and returns a result without observable side effects.

__immutable__
> The property of never changing observable state after creation.

__implicit comcept__
> A concept that is necessary to understand the meaning of a model or design but is never mentioned.

__INTENTION-REVEALING INTERFACE__
> A design in which the names of classes, methods, and other elements convey both the original developer's purpose in creating them and their value to a client developer.

__invariant__
> An ASSERTION about some design element that must be true at all times, except during specifically transient situations such as the middle of the execution of a method, or the middle of an uncommitted database transaction.

__iteration__
> A process in which a program is repeatedly improved in small steps. Also, one of those steps.

__large-scale structure__
> A set of high-level concepts, rules, or both that establishes a pattern of design ofr an entire system. A language that allows the system to be discussed and understood in broad strokes.

__LAYERED ARCHITECTURE__
> A technique for separating the concerns of a software system, isolating a domain layer, among other thing.

__life cycle__
> A sequence of states an object can take on between creation and deletion,

__model__
> A systm of abstractions that describes selected aspects of a domain and can be used to solve problems related to that domain.

__MODEL-DRIVEN DESIGN__
> A design in which soe subset of sofware eleents corresponds closely to elements of a model. Also, a process of codeveloping a model and an implementation that stay aligned with each other.

__modeling paradigm__
> A particular style of  carving out concepts in a domain, combined with tools to create software analogs of those concepts ( for example, object-oriented programming and logic programming).

__REPOSITORY__
> A mechanism for encapsulating storage, retrieval, and search bhavior which emulates a colletion of objects.

__responsibility__
> An obligation to erform a task or know information ( Wirfs-Brock et al. 2003, p.3).

__SERVICE__
> An operation offered as an interface that stands alone in the model, with no ncasulated state.

__side effect__
> Any observable change of state resulting from an operation, whether intentional or not, even a deliberate update.

__SIDE-EFFECT-FREE FUNCTION__
> See __function__.

__STANDALONE CLASS__
> A class that can be understood and tested without reference to any others, except system primitives and basic libraries.

__stateless__
> The property of a design element that allows a client to use any of its operations without regard to the element's history. A stateless element may use information that is accessible globally and may even change that global information( that is, it ma have side effects) but holds no rivate state that affects its behavir.

__strategic design__
> Modeling and design decisions that apply to large parts of the system. Such decisions affect the entire project and have to be decided at team level.

__supple design__
> A design that puts the power inherent in a deep model into the hands of a client developer to make clear, flexible expressions that give expected results robustly. Equally iportant, it leverages that same deep model to make the design itself easy for the implementer to mold and reshape to accommodate new insight.

__UBIQUITOUS LANGUAGE__
> A language structured arund the domain model and used by all team membeers to connect all the activities of the team with the soft ware.

__unification__
> The internal consistency of a model such that each term is unambiguous and no rules contradict.

__VALUE OBJECT__
> An object that describes some characteristic or attribute but carries no concept of identity.

__WHOLE VALUE__
> An oject that models a single, complete concept.
