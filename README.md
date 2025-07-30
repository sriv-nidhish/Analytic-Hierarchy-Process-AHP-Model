# AHP Model for EV Adoption – Interactive Excel Dashboard
Analytic Hierarchy Process (AHP) model used in "Investigation of factors influencing EV adoption in India’s context" research paper

---

## 1. How to Use

- **Download** [`ahp-dashboard.xlsx`](docs/Dynamic_AHP_model.xlsx) from this repository.
- **Open** the file using Microsoft Excel (Office 365 or Excel 2016+ recommended).
- **Edit** the green-highlighted cells in the pairwise comparison matrix—these are your input judgments.
- **View Results**: Criteria weights, rankings, and a consistency check update *instantly* via built-in formulas.

---

## 2. What is an AHP Model?

> **AHP (Analytic Hierarchy Process)** is a structured decision-support tool designed to help you rank options or criteria in complex decisions.
- Compares options in pairs to help you articulate and quantify preferences.
- Transforms subjective assessments into clear, rational numeric priorities.
- Extensively used in business, research, and engineering for multi-criteria decision-making.

---

## 3. How Does This Model Work?

1. **Pairwise Comparison Matrix**  
   Rate each criterion against every other to indicate relative importance.
2. **Criteria Weights & Rankings**  
   The model calculates how important each criterion is (their weights), and gives you a clear ranking.
3. **Real-Time Interactivity**  
   Changing any matrix input immediately updates all outputs—thanks to Excel’s live formulas.
4. **Visual Feedback**  
   Bar charts, conditional coloring, and a summary panel provide at-a-glance insights into top priorities and model health.

---

## 4. Consistency of the Model: What Is It?

- **AHP checks for logical consistency in your pairwise judgments** using the _Consistency Ratio (CR)_.
- **Calculation Steps:**
  - Calculate the maximum eigenvalue (**λmax**) of the matrix.
  - Compute the **Consistency Index (CI)**:
    ```
    CI = (λmax - n) / (n - 1)
    ```
  - Divide CI by the Random Index (RI, depends on n) to get CR:
    ```
    CR = CI / RI
    ```
- **Acceptance Criteria:**
  - **CR < 0.10** (<10%): Judgments are consistent—results are trustworthy.
  - **CR ≥ 0.10**: Judgments are too inconsistent—review or adjust the matrix.

---

## 5. Our Model’s Consistency Check

> ### Current Model Results:
> - **λmax:** 11.28951124
> - **CI:** 0.1432790271
> - **CR:** 0.09616042089
>
> **Status:** ✅ The Consistency Ratio is **below 0.10**, so **this AHP model is acceptably consistent**. The rankings and weights can be used confidently for decision-making.
>
> *If you modify matrix values, the model will instantly recalculate all checks so you always know if your judgments remain sound.*

---

## Example Workflow

1. Download and open the Excel file.
2. Enter your own pairwise comparison ratings in the pairwise comparison matrix.
3. Watch as the criteria weights, rankings, and consistency status update automatically.
4. Use the included charts and summary boxes for a clear decision overview.

---


## About

This AHP model template is intended for transparent, interactive, and professional multi-criteria decision-making.  
Questions? Suggestions? Please open an issue or start a discussion!

