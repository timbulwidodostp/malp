# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Maximum agreement regression Use malp With (In) R Software
install.packages("remotes")
remotes::install_github("pchausse/malp")
library("malp")
malp = read.csv("https://raw.githubusercontent.com/timbulwidodostp/malp/main/malp/malp.csv",sep = ";")
# Estimation Maximum agreement regression Use malp With (In) R Software
malp <- malp(malp ~ malp_1 + malp_2 + malp_3, malp)
summary(malp)
# Maximum agreement regression Use malp With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished