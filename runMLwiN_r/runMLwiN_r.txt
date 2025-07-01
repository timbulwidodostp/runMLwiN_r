# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Run the MLwiN multilevel modelling software Use runMLwiN (R2MLwiN) from within R Software
install.packages("R2MLwiN")
library("R2MLwiN")
# Estimation Run the MLwiN multilevel modelling software Use runMLwiN (R2MLwiN) from within R Software
options(MLwiN_path="C:/Program Files (x86)/MLwiN trial/i386/mlwin.exe")
runMLwiN_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/runMLwiN_r/main/runMLwiN_r/runMLwiN_r.csv",sep = ";")
runMLwiN <- runMLwiN(normexam ~ cons + standlrt + (1 | student), data = runMLwiN_r)
summary(runMLwiN)
# Run the MLwiN multilevel modelling software Use runMLwiN (R2MLwiN) from within R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
