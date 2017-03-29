# qAnalyze
*Average analyzer for KNUST

This is an android app to calculate for the *average score* (x/100) that a user would be working for in each registered course when the user provides his/her current CWA and target CWA.
Phase I: Only the average score for the registered courses will be calculated and displayed to the user.
Phase II: After the average score is calculated, the user has the option of providing actual/supposed mid-sem score for each course or selected courses, and the application calculates the the exam score based on the previously calculated average. Thus after the user gets to know the average score to work towards, he/she may choose to estimate the mid-sem & exam scores that will add up to the calculated average score. The user may vary the mid-sem or exam score for each indivual course.
Within the application, there will also be a link the KNUST portal to allow users verify their results before providing inputs if need be.

USER INPUTS:*
Current CWA
Cummulative Credit Hours (CummCredits)
Number of credit hours for the current semester (SemCreditHours)  
Target CWA

FORMULAE FOR THE MATHEMATICAL CALCULATIONS:
CurrentTotalScore = CurrentCWA x CummCredits
TargetTotalScore = TargetCWA x (CummCredits + SemCreditHours)
TargetSemesterScore = TargetTotalScore - CurrentTotalScore
TargetSemesterAverage = TargetSemesterScore/SemCreditHours
