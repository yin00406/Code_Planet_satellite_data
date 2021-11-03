## Planet Command Line

```
# install planet package
conda install -c conda-forge planet
```

#### Mosaic examples

```python
#t Sign in
planet init

#t Get basic information for a specific mosaic
planet mosaics info ps_monthly_normalized_analytic_L16_subscription_2021_06_mosaic

#t Download all quads in a mosaic
planet mosaics download ps_monthly_normalized_analytic_L16_subscription_2021_06_mosaic

#t Download all quads inside of a rectangular box for a mosaic
planet mosaics download ps_monthly_normalized_analytic_L16_subscription_2021_06_mosaic --bbox=1.400165,7.135936,3.158292,10.074570 --dest /scratch.global/yin00406/planet_cashew/202106
# --bbox: left,bottom,top,right (no blank between them)
# 1.400165,7.135936,3.158292,10.074570: the extent of study region in Benin
# the extent of check region in Benin: 1.823249, 9.016631, 2.745975, 9.837525


```

