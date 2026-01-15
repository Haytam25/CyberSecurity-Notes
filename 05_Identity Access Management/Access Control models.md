

## a. **Discretionary Access Control (DAC)**
- Resource **owner decides** who can access the resource.
- Common in consumer OS (e.g., Windows).
- **Flexible**, but less secure.

## b. **Mandatory Access Control (MAC)**
- Access based on **security labels** (e.g., Top Secret, Confidential).
- Defined by the system, **not user-controlled**.
- Used in **government/military** environments.

## c. **Role-Based Access Control (RBAC)**
- Access granted based on **user’s role**.
- Enforces the **principle of least privilege**.
- Easier to manage for **large organizations**.

## d. **Attribute-Based Access Control (ABAC)**
- Access is based on **user, resource, and environment attributes**.
- Very **granular** and dynamic.
- Example: `If user.department == HR AND location == Office THEN allow access`.

## e. **Rule Based Access Control (RBAC)**