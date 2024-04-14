## Volume indicator

```angular2html
from ta import volume
```
library import를 진행해준 뒤, 다음과 같이 계산이 가능하다


### money flow index (MFI)

```angular2html
money_flow_index(
    high : pandas.Series, 
    low : pandas.Series, 
    close : pandas.Series, 
    volume : pandas.Series, 
    window : int = 14, 
    fillna : bool = False
) -> pandas.Series
```

### accumulation / distribution index (ADI)

```angular2html
acc_dist_index(
    high : pandas.Series,
    low : pandas.Series,
    close : pandas.Series,
    volume : pandas.Series,
    fillna : bool = False
) -> pandas.Series
```

### on balance volume (OBV)

```angular2html
on_balance_volume(
    close : pandas.Series,
    volume : pandas.Series,
    fillna : bool = False
) -> pandas.Series
```

### chaikin money flow (CMF)
```angular2html
chaikin_money_flow(
    high : pandas.Series,
    low : pandas.Series,
    close : pandas.Series,
    volume : pandas.Series,
    window : int = 20,
    fillna : bool = False
) -> pandas.Series
```

### force index (FI)
```angular2html
force_index(
    close : pandas.Series,
    volume : pandas.Series,
    window : int = 13,
    fillna : bool = False
) -> pandas.Series
```

### ease of movement (EoM, EMV)

```angular2html
ease_of_movement(
    high : pandas.Series,
    low : pandas.Series,
    volume : pandas.Series,
    window : int = 14,
    fillna : bool = False
) -> pandas.Series

sma_ease_of_movement(
    high : pandas.Series,
    low : pandas.Series,
    volume : pandas.Series,
    window : int = 14,
    fillna : bool = False
) -> pandas.Series
```

### volume price trend (VPT)
```angular2html
volume_price_trend(
    close : pandas.Series,
    volume : pandas.Series,
    fillna : bool = False
) -> pandas.Series
```

### negative volume index (NVI)
```angular2html
negative_volume_index(
    close : pandas.Series,
    volume : pandas.Series,
    fillna : bool = False
) -> pandas.Series
```

### volume weighted average price (VWAP)
