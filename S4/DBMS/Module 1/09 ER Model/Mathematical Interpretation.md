# Mathematical Interpretation

Mathematically, an attribute A of entity set E whose value set is V can be defined as a function from E to the power set P(V) of V--> **A : E → P(V)**

We refer to the value of attribute A for entity e as A(e).

The previous definition covers both single-valued and multivalued attributes, as well as NULLs.
A NULL value is represented by the empty set.

For single-valued attributes, A(e) is restricted as singleton set for each entity e in E, whereas there is no restriction on multi-valued attributes.

For a composite attribute A, the value set V is the power set of the Cartesian product of P(V1), P(V2), . . . , P(Vn), where V1 , V2 , . . . , Vn are the value sets of the simple component attributes that form A:
			V = P(P(V1) × P(V2) × . . . × P(Vn))

