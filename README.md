## Effect of a New Inhaled Therapy on Lung Function in Mild Asthma

A randomized controlled trial evaluates a new inhaled corticosteroid (ICS-X) 
compared to a standard inhaler in patients with mild persistent asthma.

Patients are randomized to receive either ICS-X or standard therapy for 6 weeks. 
Lung function is assessed at baseline and at follow-up using FEV₁ (forced expiratory 
volume in 1 second).

***The primary endpoint is improvement in FEV₁.***

### Variables

-   *Outcome:*

    fev1_improvement: change in FEV₁ (liters) from baseline to 6 weeks

-   *Continuous predictors:*

    -   age: patient age (years)
    -   baseline_fev1: baseline FEV₁ (liters)

-   Categorical predictors:

    -   treatment_group: randomized treatment ("standard_inhaler", "ICSX")

    -   smoking_status: smoking status ("never", "former", "current")

### Hypotheses:
-   ICS-X leads to greater improvement in FEV₁
-   Higher baseline FEV₁ is associated with less room for improvement
-   Smokers exhibit a reduced treatment response
-   A negative Age effect on improvement
