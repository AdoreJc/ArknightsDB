# Act9D0ResUtil

**Namespace:** `Torappu.Activity.Act9D0`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0ResUtil
{
	public const String ACT_LOCAL_CACHE_PREFIX_WATCHED_FAVOR_UP_CHAR_ID; // 0x0
	public const String ACT_LOCAL_CACHE_PREFIX_ACCESSED_ZONE_ID; // 0x0
	public const Single ACT_NEWS_PARAM; // 0x0
	public const Int32 ACT_NEWS_PARAM_2; // 0x0
	public const Int64 ACT_NEWS_READ_LIMIT; // 0x0
	public const Int64 ACT_NEWS_READ_LIMIT_2; // 0x0
	public const String ANIM_NORMAL_START_KEY; // 0x0
	private const String ANIM_ALL_TIMEOUT_START_KEY; // 0x0
	private const String ANIM_SKIP_KEY; // 0x0

	public static String activityId { get; }
	public static UIItemCard uiItemCard { get; }
	public static StateEngine floatStateEngine { get; }
	public static BasicData basicData { get; }

	// RVA: 0x319ab04 VA: 0x75957b2b04
	public static String get_activityId() { }
	// RVA: 0x319abbc VA: 0x75957b2bbc
	public static UIItemCard get_uiItemCard() { }
	// RVA: 0x319abdc VA: 0x75957b2bdc
	public static StateEngine get_floatStateEngine() { }
	// RVA: 0x319ac80 VA: 0x75957b2c80
	public static BasicData get_basicData() { }
	// RVA: 0x319ad10 VA: 0x75957b2d10
	public static CommonTopMenu CreateCommonTopMenu(RectTransform container, Action onBackClick) { }
	// RVA: 0x319ae28 VA: 0x75957b2e28
	public static Act9D0Data GetAct9D0Data() { }
	// RVA: 0x319aec0 VA: 0x75957b2ec0
	public static Boolean IsActMissionUseTemplateStyle() { }
	// RVA: 0x319af4c VA: 0x75957b2f4c
	public static Void SetFavorUpCharWatched(String charId) { }
	// RVA: 0x319b008 VA: 0x75957b3008
	public static Boolean isFavorUpCharWatched(String charId) { }
	// RVA: 0x319b068 VA: 0x75957b3068
	public static Void SetZoneAccessed(String zoneId) { }
	// RVA: 0x319b0bc VA: 0x75957b30bc
	public static Boolean isZoneAccessed(String zoneId) { }
	// RVA: 0x319b11c VA: 0x75957b311c
	public static Sprite GetAct9D0NewsContentImg(String actId, String newsPic) { }
	// RVA: 0x319b184 VA: 0x75957b3184
	public static Sprite GetAct9D0NewsTitleImg(String actId, String titlePic) { }
	// RVA: 0x319b1ec VA: 0x75957b31ec
	public static Sprite GetAct9D0NewsLogoImg(String actId, String logoPic) { }
	// RVA: 0x319b254 VA: 0x75957b3254
	public static Sprite GetAct9D0NewsLogoLargeImg(String actId, String logoPic) { }
	// RVA: 0x319afa0 VA: 0x75957b2fa0
	private static String _GenerateActLocalCacheKey(String prefix, String id) { }
	// RVA: 0x319b2bc VA: 0x75957b32bc
	public static String GetActEntryAnimKey(ActEntryAnimKeyParams param) { }
	// RVA: 0x319b340 VA: 0x75957b3340
	public Void .ctor() { }
}
```