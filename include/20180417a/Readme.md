# `20180417a` -- Comparing modules vs echOmods

## Files

* [un0rick acqs](/include/20180417a/20180403a.npz)
* [Raspberry Pi acqs](/include/20180417a/20180415r.npz)
* [Jupyter notebook](/include/20180417a/20180417a-Comparison.ipynb)

## Results

Let's compare the acquisitions with the modules compare to the un0rick board. At a reduced speed for the un0rick, the acquisitions are quite comparable, showing similar acquisitions at 21Msps and 22.5Msps.

Blue is from the raspberry board, red from un0rick.Now, going on the details of the acquisitions. we see that the level of acquisitions are higher (which is normal as the range of the un0rick gets data on 10bits, whereas the pHAT is on 9 bits).

Moreover, the last acquisition, at ~120us, appears quite nicely with un0rick, whereas it is off the radar on the modules.

![](/include/20180417a/comparing.jpg)

​One can also see that the level of noise has improved by a factor of 4.. or more.

![](/include/20180417a/details.jpg)

But I'd need to be more rigourous to get precise numbers =)

Log as usual is available.
