```
public static FakeAd getLocalAd(Context context) {
  FakeAd fakeAd = new FakeAd();

  fakeAd.setTitle("Snowy 輕鬆進入滑雪世界");
  fakeAd.setContent("國際認證教練，享受滑雪的樂趣");
  fakeAd.setCta("預約滑雪課程");
  fakeAd.setIconUrl("https://www.snowy.fun/bus_plus/icon.png");
  fakeAd.setMediaContentUrl("https://www.snowy.fun/bus_plus/banner_760x428.png");
  String intentUrl = "https://www.snowy.fun/";
  fakeAd.setIntent(new Intent(Intent.ACTION_VIEW, Uri.parse(intentUrl)));
  fakeAd.setIntentUrl(intentUrl);

  return fakeAd;
}
```
