### DASHBOARD 1
%TotalCallsAnswered = DIVIDE([CallsAnswered],COUNT('Sheet1'[Call Id]))

CallsAnswered = CALCULATE(COUNT('Sheet1'[Answered (Y/N)]),'Sheet1'[Answered (Y/N)]="Y")

CallsMissed = CALCULATE(COUNT('Sheet1'[Answered (Y/N)]),'Sheet1'[Answered (Y/N)]="N")

IssueResolved = CALCULATE(COUNT('Sheet1'[Resolved]),'Sheet1'[Resolved]="Y")


### DASHBOARD 2
Churn Rate% = DIVIDE(CALCULATE(count('01 Churn-Dataset'[Churn]),'01 Churn-Dataset'[Churn]="Yes"),count('01 Churn-Dataset'[Churn]))

Count of Churn Yes = CALCULATE(Count('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[Churn]="Yes")

%CustomersAtRisk = DIVIDE(Calculate(count('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[Churn]="Yes"),count('01 Churn-Dataset'[customerID]))

%DeviceProtection = DIVIDE(CALCULATE(count('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[DeviceProtection]="Yes"),count('01 Churn-Dataset'[customerID]))

%ofDependents = Divide(CALCULATE(COUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[Dependents]="Yes"),Count('01 Churn-Dataset'[customerID]))

%ofPartners = Divide(CALCULATE(COUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[Partner]="Yes"),COUNT('01 Churn-Dataset'[customerID]))

%OnlineBackup = DIVIDE(CALCULATE(count('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[OnlineBackup]="Yes"),count('01 Churn-Dataset'[customerID]))

%OnlineSecurity = DIVIDE(CALCULATE(count('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[OnlineSecurity]="Yes"),count('01 Churn-Dataset'[customerID]))

%PhoneService = DIVIDE(CALCULATE(COUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[PhoneService]="Yes"),COUNT('01 Churn-Dataset'[customerID]))

%SeniorCitizen = Divide(SUM('01 Churn-Dataset'[SeniorCitizen]),COUNT('01 Churn-Dataset'[customerID]))

%StreamingMovies = DIVIDE(CALCULATE(count('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[StreamingMovies]="Yes"),count('01 Churn-Dataset'[customerID]))

%StreamingTV = DIVIDE(CALCULATE(count('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[StreamingTV]="Yes"),count('01 Churn-Dataset'[customerID]))


### DASHBOARD 3
% Women Leavers = DIVIDE(CALCULATE(COUNT('Pharma Group AG'[Employee ID]),'Pharma Group AG'[Gender]="Female",'Pharma Group AG'[FY20 leaver?]="Yes"),COUNT('Pharma Group AG'[Employee ID]))

%OfNewHireFemale = DIVIDE(CALCULATE(COUNT('Pharma Group AG'[Employee ID]),'Pharma Group AG'[Gender]="Female",'Pharma Group AG'[New hire FY20?]="Y"),CALCULATE(COUNT('Pharma Group AG'[Employee ID]),'Pharma Group AG'[New hire FY20?]="Y"))

%OfNewHireMen = DIVIDE(CALCULATE(COUNT('Pharma Group AG'[Employee ID]),'Pharma Group AG'[Gender]="Male",'Pharma Group AG'[New hire FY20?]="Y"),CALCULATE(count('Pharma Group AG'[Employee ID]),'Pharma Group AG'[New hire FY20?]="Y"))

%PromotionFY21 = DIVIDE(CALCULATE(count('Pharma Group AG'[Employee ID]),'Pharma Group AG'[Promotion in FY20?]="Y"),COUNT('Pharma Group AG'[Employee ID]))

%WomenPromoted = DIVIDE(CALCULATE(count('Pharma Group AG'[Employee ID]), 'Pharma Group AG'[Gender]="Female",'Pharma Group AG'[Promotion in FY20?]="Y"),CALCULATE(COUNT('Pharma Group AG'[Employee ID]),'Pharma Group AG'[Promotion in FY20?]="Y" ))

avgMenPerformanceRating = CALCULATE(AVERAGE('Pharma Group AG'[FY20 Performance Rating]),'Pharma Group AG'[Gender]="Male")

avgMenPerformanceRating19 = CALCULATE(AVERAGE('Pharma Group AG'[FY19 Performance Rating]),'Pharma Group AG'[Gender]="Male")

avgWomenPerformanceRating = CALCULATE(AVERAGE('Pharma Group AG'[FY20 Performance Rating]),'Pharma Group AG'[Gender]="Female")

avgWomenPerformanceRating19 = CALCULATE(AVERAGE('Pharma Group AG'[FY19 Performance Rating]),'Pharma Group AG'[Gender]="Female")

NofMen = DIVIDE(CALCULATE(COUNT('Pharma Group AG'[Employee ID]),'Pharma Group AG'[Gender]="Male"),COUNT('Pharma Group AG'[Employee ID]))

NofWomen = DIVIDE(CALCULATE(COUNT('Pharma Group AG'[Employee ID]),'Pharma Group AG'[Gender]="Female"),COUNT('Pharma Group AG'[Employee ID]))

NoOfLeavers = CALCULATE(count('Pharma Group AG'[Employee ID]),'Pharma Group AG'[FY20 leaver?]="Yes")

