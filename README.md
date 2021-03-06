## Technical analysis library for Delphi (coming soon...)

![Indicators4D Logo](Indicators4D.jpg)

### Sample for Relative Strength Index (RSI) usage:

```delphi
  var rsi := TRSI.Create(14);
  var ohlcList := TList<TOhlc>.Create;
  // fill ohlcList
  rsi.Load(ohlcList);
  var serie := rsi.Calculate();
```

### Library includes the following implementations:
- Accumulation/Distribution (ADL) 
- Average Directional Index (ADX)
- Aroon
- Average True Range (ATR)
- BollingerBand
- Commodity Channel Index (CCI)
- Chaikin Money Flow (CMF)
- Chande Momentum Oscillator (CMO)
- Double Exponential Moving Average (DEMA)
- Detrended Price Oscillator (DPO)
- Exponential Moving Average (EMA)
- Moving Average Envelopes (Envelope)
- Ichimoku Clouds (Ichimoku)
- Moving Average Convergence Divergence (MACD)
- Momentum
- On Balance Volume (OBV)
- Price Volume Trend (PVT)
- Rate of Change (ROC)
- Relative Strength Index (RSI)
- Stop and Reverse (SAR)
- Simple Moving Average (SMA)
- TRIX
- Volume
- Volume Rate of Change (VROC)
- Weighted Moving Average (WMA)
- Williams %R (WPR)
- Zero Lag EMA (ZLEMA)
