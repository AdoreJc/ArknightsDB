# CrisisV2ShopPage

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`


## Methods

- `Void _ReturnPage()`

- `Void <OnCreate>b__2_0(GameObject)`

- `Void <OnCreate>b__2_1()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2ShopPage : StateEnginePage
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xe8
	private static DelegateBridge __Hotfix0__ReturnPage; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_LoadShopIcon; // 0x10
	private static DelegateBridge __Hotfix0_LoadShopTitle; // 0x18
	private static DelegateBridge __Hotfix0_LoadShopBackPic; // 0x20
	private static DelegateBridge __Hotfix0_LoadSeasonResHolder; // 0x28
	private static DelegateBridge __Hotfix0__LoadAutoPackSprite; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2bc8908 VA: 0x75951e0908
	private Void _ReturnPage() { }
	// RVA: 0x2bc89b8 VA: 0x75951e09b8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2bc8aa0 VA: 0x75951e0aa0
	public static Sprite LoadShopIcon(String seasonId, CrisisShopVer shopVer) { }
	// RVA: 0x2bc8cb0 VA: 0x75951e0cb0
	public static SpriteRenderData LoadShopTitle(String seasonId, ILoadAsset loadAsset) { }
	// RVA: 0x2bc8ff0 VA: 0x75951e0ff0
	public static Sprite LoadShopBackPic(String picId, CrisisShopVer shopVer) { }
	// RVA: 0x2bc90a0 VA: 0x75951e10a0
	public static CrisisStageSeasonResHolder LoadSeasonResHolder(String seasonId) { }
	// RVA: 0x2bc8b34 VA: 0x75951e0b34
	private static Sprite _LoadAutoPackSprite(String spriteId, String hubPath) { }
	// RVA: 0x2bc9214 VA: 0x75951e1214
	public Void .ctor() { }
	// RVA: 0x2bc9284 VA: 0x75951e1284
	private Void <OnCreate>b__2_0(GameObject inst) { }
	// RVA: 0x2bc933c VA: 0x75951e133c
	private Void <OnCreate>b__2_1() { }
	// RVA: 0x2bc9340 VA: 0x75951e1340
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```