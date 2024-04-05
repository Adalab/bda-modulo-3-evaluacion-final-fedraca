##EVALUACION FINAL MODULO 3##

LA SIGUIENTE EVALUACION TIENE COMO OBJETIVO  EL  ANALISIS Y TRANFORMACION DE UNOS DATOS YA DADOS.

PARA LO SIGUIENTE  UTILIZAREMOS EL PROCESO EDA PARA LA COMPRENSION DE NUESTROS DATOS, DESPUES HAREMOS UNA LIMPIEZA DE LOS MISMOS PARA PODER TRANFORMARLOS Y PODER ANALIZARLOS DE UNA MEJOR MANERA.

HAREMOS UNA VISUZALIZACION PARA COMPRENDER LOS DATOS Y ALGUNAS PREGUNTAS QUE SE NOS HACEN EN LA EVALUACION Y UNA EXPLICACION DE CADA GRAFICA 
POR ULTIMO HAREMOS UN A/B TESTING 

PARA EL SIGUIENTE ANALISIS DEBEMOS TENER INSTALADA UNA SERIA DE BIBLIOTECAS PARA EL TRATAMIENTO  CORRECTO DE NUESTROS DATOS. 

""" 
Tratamiento de datos
# -----------------------------------------------------------------------
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
# Evaluar linealidad de las relaciones entre las variables
# y la distribución de las variables
# ------------------------------------------------------------------------------
import scipy.stats as stats
from scipy.stats import ttest_ind, norm, chi2_contingency
from scipy.stats import shapiro
from scipy.stats import mannwhitneyu
from sklearn.linear_model import LinearRegression


# Imputación de nulos usando métodos avanzados estadísticos
# -----------------------------------------------------------------------
from sklearn.impute import SimpleImputer
from sklearn.experimental import enable_iterative_imputer
from sklearn.impute import IterativeImputer
from sklearn.impute import KNNImputer

# Configuración
# -----------------------------------------------------------------------
pd.set_option('display.max_columns', None) # para poder visualizar todas las columnas de los DataFrames
"""

