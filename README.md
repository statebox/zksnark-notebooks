# zksnark-notebooks

QAP is a SageMath notebook that constructs the polynomials in a Quadratic Arithmetic Program, which is the first stage of constructing a zkSNARK.

This notebook shows how a small arithmetic circuit is transformed into a polynomial. A assignment to the circuit is correct if and only if the created polynomial is divisible by a target polynomial.

The next steps for this notebook are to include the elliptic curve cryptography necessary to hide the private inputs. 
