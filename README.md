# UML-HRTech
#Example
1: Association
- Customer (1) - association - Entitlement(0 or more)
- Customer - association - BatchCode
- Customer <- Aggreciation - Company
- Customer <- Aggreciation - Individual

2. Entitlement
- Entitlement (0 or more) - association - Produce

3. Produce
- Produce (0 or more) - association - BathCode(1)
- Produce (0 or more) <>- Aggreciation - Feature (1 or more)
- produce (0 or more) -<.> Composition

4. Feature 
- Feature (0 or more) - association - BathCode

5. Details
- Details - Composition -<.> Individual
- Details - Composition -<.> Company

6. Contact
- Contact - Composition -<.> Company
