# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Kernel partial correlation with RKHS method Use KPCRKHS (KPC) With (In) R Software
install.packages("KPC")
library("KPC")
KPCRKHS = read.csv("https://raw.githubusercontent.com/timbulwidodostp/KPCRKHS/main/KPCRKHS/KPCRKHS.csv",sep = ";")
# Estimation Kernel partial correlation with RKHS method Use KPCRKHS (KPC) With (In) R Software
library(kernlab)
k = vanilladot()
n = 500
KPCRKHS(KPCRKHS$y, KPCRKHS$x, KPCRKHS$z, k, k, k, 1e-3/n^(0.4), appro = FALSE)
KPCRKHS(KPCRKHS$y, KPCRKHS$x, KPCRKHS$z, k, k, k, 1e-3/n^(0.4), appro = TRUE, tol = 1e-5)
# Kernel partial correlation with RKHS method Use KPCRKHS (KPC) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished