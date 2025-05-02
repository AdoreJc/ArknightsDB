# Act4D0ResUtil

**Namespace:** `Torappu.Activity.Act4D0`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0ResUtil
{
	private const String HEAD_ICON; // 0x0
	private const String LARGE_IMAGE; // 0x0
	private const String HUB_PATH_FORMAT; // 0x0
	public static Single MILESTONE_HEIGHT; // 0x0
	public static Single MILESTONE_DELTA_HEIGHT; // 0x4
	public static Single MILESTONE_OFFSET; // 0x8

	public static UIItemCard uiItemCard { get; }
	public static CommonTopMenu commonTopMenu { get; }
	public static PlayerAct4D0Activity playerInfo { get; }
	public static Act4D0Data act4d0Data { get; }
	public static BasicData basicData { get; }
	public static SpriteHub entrySpriteHub { get; }
	public static UIItemViewModel mileStoneToken { get; }

	// RVA: 0x31d9fec VA: 0x75957f1fec
	public static Sprite GetStoryImage(String storyKey, Boolean largeFlag) { }
	// RVA: 0x31da2a4 VA: 0x75957f22a4
	public static UIItemCard get_uiItemCard() { }
	// RVA: 0x31da2c4 VA: 0x75957f22c4
	public static CommonTopMenu get_commonTopMenu() { }
	// RVA: 0x31da2e4 VA: 0x75957f22e4
	public static PlayerAct4D0Activity get_playerInfo() { }
	// RVA: 0x31da4bc VA: 0x75957f24bc
	public static StoryInfo GetStoryInfo(String storyId) { }
	// RVA: 0x31da540 VA: 0x75957f2540
	public static Act4D0Data get_act4d0Data() { }
	// RVA: 0x31da688 VA: 0x75957f2688
	public static BasicData get_basicData() { }
	// RVA: 0x31da718 VA: 0x75957f2718
	public static PlayerAct4D0Activity GetAct4D0PlayerInfo(String actId) { }
	// RVA: 0x31da79c VA: 0x75957f279c
	public static PlayerAct4D0Activity GetAct4D0PlayerInfoFromPlayerData(String actId, PlayerDataModel playerModel) { }
	// RVA: 0x31da160 VA: 0x75957f2160
	public static SpriteHub get_entrySpriteHub() { }
	// RVA: 0x31da820 VA: 0x75957f2820
	public static UIItemViewModel get_mileStoneToken() { }
	// RVA: 0x31da8d8 VA: 0x75957f28d8
	public Void .ctor() { }
	// RVA: 0x31da8e0 VA: 0x75957f28e0
	private static Void .cctor() { }
}
```