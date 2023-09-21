# clase-2-programacion
analisis que estamos haciendo en la clase
lo que quieran
ggbetweenstats(
  data = varcrot2,
  x = Sito,
  y = Altitud,
  type = "parametric", # ANOVA or Kruskal-Wallis
  var.equal = TRUE, # ANOVA or Welch ANOVA
  plot.type = "box",
  pairwise.comparisons = TRUE,
  pairwise.display = "significant",
  centrality.plotting = TRUE,
  bf.message = TRUE
)

#Scrib_of_data
estructura: Nombre= comando(base de datos, características)</h2>
#para insatalar una libreria#
install.packages("raster")

#para cargar una libreria
library(raster)

#para definir el escritorio de trabajo#
setwd("C:Users/ALUMNO.PC4COMPUTOA/desktop")

#clasificate of analitys in the program
my_character="universe"
my_logical=FALSE
my_numeric=42

#clasificate of class on the sistem 
class(my_numeric)
class(my_character)
class(my_logical)

#create the numeric vector and the character vector
Vegas="go!"
Vegas
numeric_vector=c(1,10,49)
character_vector=c("a","b","c")
boolean_vector=c(TRUE,FALSE,TRUE)
poker_vector=c(140,-50,20,-120,240)
roulette_vector=c(-24,-50,100,-350,10)
names(poker_vector)=c("mondar","tuesday","wednesday","thursday","friday")
names(poker_vector)=c("monday","tuesday","wednesday","thursday","friday")
names(roulette_vector)=c("monday","tuesday","wednesday","thursday","friday")

#the variables day vector
days_vectors=c("monday","tuesday","wednesday","thursday","friday")

#assing the names of the day to roulette vector and poker vector
names(roulette_vector)=days_vectors
names(poker_vector)=days_vectors

#resultados
total_daily=poker_vector+roulette_vector
#total winning  in the poker
total_poker=sum(poker_vector)
#total winning  in the roulette
total_roulette=sum(roulette_vector)
#print out total week
total_week=total_roulette+total_poker

#comparative with boleanne results
total_poker>total_roulette
total_poker<total_roulette

#Define a new variable based on a selection
poker_wednesday=poker vector[3]
poker_midweek=poker_vector[c(2,3,4)]
#Created intervalos
roulette_selection_vector=roulette_vector[2:5]
 poker_start=poker_vector[c("monday","tuesday","wednesday")]

#Browse teh promedy
mean(poker_start)
#Elaborado por Jesús Eduardo Huitrón Lemus
