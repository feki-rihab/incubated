# ExcDC3A1


## Description
This is modified old IEEE type 3 excitation system.

## Data Model
  - properties:
    - ka:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage regulator gain (Ka).  Typical Value = 300. Default: 0.0
    - ta:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage regulator time constant (Ta).  Typical Value = 0.01. Default: 0
    - vrmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum voltage regulator output (Vrmax).  Typical Value = 5. Default: 0.0
    - vrmin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum voltage regulator output (Vrmin).  Typical Value = 0. Default: 0.0
    - te:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter time constant, integration rate associated with exciter control (Te).  Typical Value = 1.83. Default: 0
    - kf:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Excitation control system stabilizer gain (Kf).  Typical Value = 0.1. Default: 0.0
    - tf:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Excitation control system stabilizer time constant (Tf).  Typical Value = 0.675. Default: 0
    - kp:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Potential circuit gain coefficient (Kp).  Typical Value = 4.37. Default: 0.0
    - ki:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Potential circuit gain coefficient (Ki).  Typical Value = 4.83. Default: 0.0
    - vbmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Available exciter voltage limiter (Vbmax).  Typical Value = 11.63. Default: 0.0
    - exclim:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : (exclim). true = lower limit of zero is applied to integrator output false = lower limit of zero not applied to integrator output. Typical Value = true. Default: False
    - ke:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter constant related to self-excited field (Ke).  Typical Value = 1. Default: 0.0
    - vb1max:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Available exciter voltage limiter (Vb1max).  Typical Value = 11.63. Default: 0.0
    - vblim:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Vb limiter indicator. true = exciter Vbmax limiter is active false = Vb1max is active.  Typical Value = true. Default: False