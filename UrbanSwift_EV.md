# UrbanSwift EV — Test Vehicle 01

## Vehicle Overview

- Vehicle type: 5-seat electric hatchback
- Intended use: Urban / general-purpose electric vehicle
- Vehicle mass: 1,450 kg
- Drivetrain: Front-wheel drive (FWD)

## Performance Targets

- Target top speed: 180 km/h
- Target 0–100 km/h: 5 seconds
- Target range: 600 km

## Battery

- Battery capacity: 20 kWh
- Architecture: 400 V
- Chemistry: Lithium-ion
- Cooling: Not specified

## Charging

- Maximum DC charging power: 150 kW
- Target charging time: 10–80% in 10 minutes

## Electric Motor

- Motor type: PMSM
- Peak power: 200 kW
- Maximum torque: 400 Nm
- Motor layout: Front
- Drive: FWD

## Wheels and Tires

- Wheel diameter: 14 inches
- Tire type: Narrow, low-rolling-resistance tires
- Load index: Not specified
- Speed rating: Not specified

## Suspension

- Front: Independent suspension
- Rear: Torsion-beam suspension
- Ground clearance: 200 mm

## Braking

- Four-wheel disc brakes
- Rotor dimensions: Not specified
- Brake caliper specification: Not specified
- Target stopping distance: Not specified

## Safety and ADAS

- Target crash rating: 5-star
- Automatic Emergency Braking (AEB)
- Lane Keeping Assist (LKA)
- Adaptive Cruise Control (ACC)
- Autonomous driving capability: Claimed, level not specified
- Airbag configuration: Not specified

## Other Features

- Panoramic roof
- Low-rolling-resistance tires

## Intentional / Test Concerns

This vehicle was created as a test case for the AI-assisted engineering review system.

The design intentionally contains potentially conflicting or questionable requirements, including:

1. Very large range target relative to the small 20 kWh battery.
2. High 150 kW DC charging power relative to the battery capacity.
3. 5-second 0–100 km/h target with FWD and relatively narrow tires.
4. 14-inch wheels for a vehicle targeting 180 km/h.
5. Autonomous driving claim without specifying the automation level or sensor architecture.
6. Several important engineering parameters are intentionally missing.

## Purpose of Test

The purpose of UrbanSwift is to determine whether the Claude-based engineering reviewer can:

- Extract the supplied specifications.
- Identify missing engineering information.
- Detect potential design conflicts.
- Perform basic engineering calculations.
- Explain causes and consequences of potential flaws.
- Distinguish confirmed findings from assumptions and validation requirements.
