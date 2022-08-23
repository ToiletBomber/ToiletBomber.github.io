                                            **通过Tan(δ)计算电容ESR**

电容等效串联电阻（ESR）通常广受关注，但它不会直接在参数数据或物料规格书中标注。在这些情况下，我们可以通过**物料损耗角（δ）**的相关信息来计算ESR值。 

电容的总复阻抗在实-复数平面上表示为实数分量（ESR）和复数（无功）分量的矢量和，用以表示“理想”电容（ESR等元素在所有实际分量中均混合使用）。总阻抗与其复数分量之间的角称为“损耗角”，该数值用于概括电容总阻抗的理想和非理想分量之间的比值。

![](https://raw.githubusercontent.com/ToiletBomber/pico_repo/master/picgo/Snipaste_2022-08-23_10-02-45.png)

通常会提供损耗角的正切，因为这样比较简单。在采用理想电容的阻抗公式做代数时，我们发现，可以将规格书中的损耗角值除以2π、测试频率和电容值，从而得出ESR值。以物料号[1189-1546-3-ND](https://www.digikey.cn/products/zh?WT.z_header=search_go&keywords=1189-1546-3-ND%20) 为例，tan(δ)和f值均包含在[规格书](http://www.rubycon.co.jp/en/catalog/e_pdfs/aluminum/e_yxj.pdf)的第一页中。

![](https://raw.githubusercontent.com/ToiletBomber/pico_repo/master/picgo/Snipaste_2022-08-23_10-04-17.png)

现在只需简单地将数字填入等式中即可：   

![](https://raw.githubusercontent.com/ToiletBomber/pico_repo/master/picgo/Snipaste_2022-08-23_10-04-52.png)

请注意，此值仅适用于特定的测试条件（温度、频率等），并且会随着条件的变化而变化。

<mark>1F = 1000000uF</mark>


