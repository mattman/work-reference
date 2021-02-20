---
layout: default
title: Drug Calculations
parent: General
has_children: false
---

# Drug Calculations
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

# Basic

## Paediatric

### Weight

It's best practice to use the patients weight if known, however doesn't always happen to be to hand (especially on route to a job) so you can ballpark with these formula

#### 1-9yrs

$$ \textit{Weight} = (\text{Age} + 4) \times 2 $$

#### 10-12yrs

$$ \textit{Weight} = \text{Age} \times 3.3 $$

### Blood Pressure

#### Normal circumstances

$$ 80 + (2 \times \text{Age}) $$

#### ROSC

$$ 80 $$

#### Non-ROSC fluid target BP (i.e. Shock)

$$ 70 + (2 \times \text{Age}) $$

### Total circulating volume

80-90ml/kg

# Basic formula for drugs

$$ \frac{\text{What you want}} {\text{What you've got}} = \text{ml to be administered} $$

### Worked examples

**8 year old patient, weight unknown**

#### Weight
{: .no_toc }

$$ \begin{aligned} \textit{Weight} &= (8 + 4) \times 2 \\ &= 12 \times 2 \\ &= 24\text{kg} \end{aligned} $$

#### Ketamine:
{: .no_toc}

**Presentation:** 200mg/2ml or more importantly - 100mg/1ml

**Dosing:** For example we're going to deliver IM for analgesic purposes so initial dose is 1mg/kg

$$ 1mg/kg \times 24kg = 24mg \text{ for delivery (IM)} \\ \frac {24} {100} = 0.24\text{ml} $$

**Dosing:** An IV line is established, you also now need to consider dilution of the drug. For our purposes we will dilute 200mg/2ml with 18ml of NaCl 0.9% to achieve a concentration of 10mg/ml in a 20ml syringe (which is of course, labelled appropriately). The dosing regime is 0.1mg/kg.

$$ 0.1mg/kg \times 24kg = 2.4mg \\ \\ \frac {1.8mg} {10mg} = 0.18ml \text{ IV} $$

# Cardiac Arrest

We can use a couple of shortcuts here in an attempt to help with cognitive loading - these are only for Paeds because well, adult doses are conviently all the same

Order of operation : Weight, Joules, Fluids, Adrenaline, Amiodarone, Glucose

## Weight

See above for paeds

## Joules (Defib)

$$ \text{Weight} \times 4J $$

## Fluids (Max)
 
$$ \text{Weight} \times 20ml $$

## Adrenaline

Using 1:10000 strength which is achieved by diluting stock 1mg:1ml (1:1000) with 9ml NaCl 0.9%

$$ \text{Weight} \times 10mcg $$

## Amiodarone

$$ \text{Weight} \times 5mg $$

## Glucose

$$ \text{Weight} \times 2.5ml $$

## Shortcut method

Probably the easiest way to do this is to write the steps out and then show a worked example

 1. Calculate weight
 2. Calculate joules for defib
 3. (Joules x 10) [i.e. add a 0] divided by 2 is your Fluids amount (ml)
 4. Halve fluids for dose of Adrenaline (mcg) and divide by 100 for ml to be given
 5. Halve the Adrenaline (mcg) dose for Amiodarone dose (mg) - ml given is same as Adrenaline
 6. Halve the Amiodarone (mg) dose to give Glucose dose (ml) and divide by 10 if you want the grams

### Worked example

7 year old patient

$$ \begin{alignedat}{3} \text{Weight} &= (7 + 4) &\times 2 &= 22kg \\ \text{Joules} &= 22kg &\times 4J &= 88J \\ \text{Fluids (ml)} &= 22kg &\times 20ml &= 440ml \\ \text{Adrenaline (mcg)} &= 22kg &\times 10mcg &= 220mcg \text{ in 2.2ml} \\ \text{Amiodarone (mg)} &= 22kg &\times 5mg &= 110mg \text{ in 2.2ml} \\ \text{Glucose (ml)} &= 22kg &\times 2.5ml &= 55ml = 5.5g \end{alignedat} $$

# Volume required
{: .no_toc}

Key here is to ensure everything in same unit (so all mg or all g)

$$ \textit{Volume required} = \frac{\text{Strength required}} {\text{Stock strength}} + \frac {\text{Volume of stock}} 1 $$
