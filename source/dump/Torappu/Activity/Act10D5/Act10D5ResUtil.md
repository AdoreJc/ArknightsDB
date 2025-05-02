# Act10D5ResUtil

**Namespace:** `Torappu.Activity.Act10D5`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5ResUtil
{
	public const String ACT_LOCAL_CACHE_PREFIX_WATCHED_FAVOR_UP_CHAR_ID; // 0x0
	public const String ACT_LOCAL_CACHE_PREFIX_ACCESSED_ZONE_ID; // 0x0
	private const String CHAR_HUB_PATH; // 0x0

	public static String activityId { get; }
	public static StateEngine floatStateEngine { get; }
	public static SpriteHub act10d5SpriteHub { get; }
	public static UIItemCard uiItemCard { get; }

	// RVA: 0x347eebc VA: 0x7595a96ebc
	public static String get_activityId() { }
	// RVA: 0x347ef74 VA: 0x7595a96f74
	public static StateEngine get_floatStateEngine() { }
	// RVA: 0x347f018 VA: 0x7595a97018
	public static CommonTopMenu CreateCommonTopMenu(RectTransform container, Action onBackClick) { }
	// RVA: 0x347f130 VA: 0x7595a97130
	public static SpriteHub get_act10d5SpriteHub() { }
	// RVA: 0x347f234 VA: 0x7595a97234
	public static UIItemCard get_uiItemCard() { }
	// RVA: 0x347f254 VA: 0x7595a97254
	public static Void SetFavorUpCharWatched(String charId) { }
	// RVA: 0x347f310 VA: 0x7595a97310
	public static Boolean isFavorUpCharWatched(String charId) { }
	// RVA: 0x347f370 VA: 0x7595a97370
	public static Void SetZoneAccessed(String zoneId) { }
	// RVA: 0x347f3c4 VA: 0x7595a973c4
	public static Boolean isZoneAccessed(String zoneId) { }
	// RVA: 0x347f2a8 VA: 0x7595a972a8
	private static String _GenerateActLocalCacheKey(String prefix, String id) { }
	// RVA: 0x347f424 VA: 0x7595a97424
	public Void .ctor() { }
}
```