# PF ECR Generator

Formulae:
MPF=ROUND(PFWages*12%)
EPF=MPF+VPF
CPF=MPF-EPS
EPS Wages= IF Pension Flag Y then MIN(PFWages, Ceiling) else 0
EPS=ROUND(EPS Wages*8.33%)
EDLI Wages=MIN(PFWages, EDLI Ceiling)
Admin Charges=PFWages*Admin Rate
EDLI Charges=EDLI Wages*EDLI Rate
