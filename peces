# Dr. Byron González
# http://cete.fausac.gt
library(DataExplorer)
plot_str(peces)
introduce(peces)
# Resumen porcentual de variables
plot_intro(peces)
# Resumen porcentual de datos perdidos
plot_missing(peces)
# Resumen para variable categóricas
plot_bar(peces)
# Resumen de variables categóricas por una variable de interés
plot_bar(peces, by="especie")
# Histogramas de variables categóricas
plot_histogram(peces)
# QQ Plot de variables cuantitativas
qqdata<-peces[,c("lint","wte")]
plot_qq(qqdata)
# Correlograma para variable cuantitativas
data_corr<-peces[, c("lint","wte","lt","wt","wgon","ldig","weslleno","wstomv")]
plot_correlation(na.omit(data_corr))
# Diagramas de caja para variables cuantitativas por especie
data_box<-peces[c("lint","wte","lt","wt","wgon","ldig","weslleno","wstomv","especie")]
plot_boxplot(data_box, by="especie")
