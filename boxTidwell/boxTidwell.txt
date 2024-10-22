# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Computes the Box-Tidwell power transformations of the predictors in a linear model Use boxTidwell (car) With (In) R Software
install.packages("car")
library("car")
boxTidwell = read.csv("https://raw.githubusercontent.com/timbulwidodostp/boxTidwell/main/boxTidwell/boxTidwell.csv",sep = ";")
# Estimation Computes the Box-Tidwell power transformations of the predictors in a linear model Use boxTidwell (car) With (In) R Software
boxTidwell <- boxTidwell(prestige ~ income + education, ~ type + poly(women, 2), data=boxTidwell)
boxTidwell
# Computes the Box-Tidwell power transformations of the predictors in a linear model Use boxTidwell (car) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished