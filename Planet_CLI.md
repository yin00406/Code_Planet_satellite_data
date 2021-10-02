## Planet Command Line

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
# 1.400165,7.135936,3.158292,10.074570: the extent of study region in Benin



```

