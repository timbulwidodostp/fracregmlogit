# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimate Fractional Multinomial Logit Models Use fracregmlogit (fracreg) With (In) R Software
install.packages("fracreg")
library("fracreg")
# Estimate Fractional Multinomial Logit Models Use fracregmlogit (fracreg) With (In) R Software
fracregmlogit = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fracregmlogit/main/fracregmlogit/fracregmlogit.csv",sep = ";")
X = fracregmlogit[,2:5]
y = fracregmlogit[,6:11]
fracregmlogit = fracregmlogit(y, X)
summary(fracregmlogit)
# Estimate Fractional Multinomial Logit Models Use fracregmlogit (fracreg) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished