# MedalUtil

**Namespace:** `Torappu.UI`


## Methods

- `MedalGetState GetMedalGetState(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class MedalUtil
{
	public static readonly Color ORANGE_LIGHT_COLOR; // 0x0
	public const Single COMMON_SCALE; // 0x0
	public const Single COMMON_DETAIL_SCALE; // 0x0
	private static DelegateBridge __Hotfix0_GetMedalGetState; // 0x10
	private static DelegateBridge __Hotfix0_GetMedalIcon; // 0x18
	private static DelegateBridge __Hotfix1_GetMedalIcon; // 0x20
	private static DelegateBridge __Hotfix0_GetMedalTitle; // 0x28
	private static DelegateBridge __Hotfix0_GetAvailMedalCount; // 0x30
	private static DelegateBridge __Hotfix0_LoadMedalGroupViewPrefab; // 0x38
	private static DelegateBridge __Hotfix1_LoadMedalGroupViewPrefab; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfMedalAchieved; // 0x48
	private static DelegateBridge __Hotfix0_LoadDIYInfo; // 0x50
	private static DelegateBridge __Hotfix0_LoadCurrentDIYInfo; // 0x58
	private static DelegateBridge __Hotfix0_CheckIfSameDIYInfo; // 0x60
	private static DelegateBridge __Hotfix0_CreateMedalGroupModel4Display; // 0x68
	private static DelegateBridge __Hotfix1_CreateMedalGroupModel4Display; // 0x70
	private static DelegateBridge __Hotfix0_CheckMedalExpireStatus; // 0x78
	private static DelegateBridge __Hotfix0_GetMedalProgressDesc; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x2271b5c VA: 0x7594889b5c
	public MedalGetState GetMedalGetState(String medalId) { }
	// RVA: 0x2271be8 VA: 0x7594889be8
	public static Sprite GetMedalIcon(String medalId, String pageName) { }
	// RVA: 0x2271c84 VA: 0x7594889c84
	public static Sprite GetMedalIcon(String medalId, ILoadAsset loader) { }
	// RVA: 0x2271d20 VA: 0x7594889d20
	public static Sprite GetMedalTitle(String groupId, String pageName) { }
	// RVA: 0x2271dbc VA: 0x7594889dbc
	public static Int32 GetAvailMedalCount(IList`1 medalIdList) { }
	// RVA: 0x2271fb0 VA: 0x7594889fb0
	public static UIMedalGroupView LoadMedalGroupViewPrefab(ILoadAsset loader) { }
	// RVA: 0x22720d0 VA: 0x759488a0d0
	public static UIMedalGroupView LoadMedalGroupViewPrefab(String pageName) { }
	// RVA: 0x2272168 VA: 0x759488a168
	public static Boolean CheckIfMedalAchieved(String medalId) { }
	// RVA: 0x227226c VA: 0x759488a26c
	public static Dictionary`2 LoadDIYInfo(PlayerMedalCustomLayout customLayout) { }
	// RVA: 0x22724f0 VA: 0x759488a4f0
	public static Dictionary`2 LoadCurrentDIYInfo() { }
	// RVA: 0x22726d0 VA: 0x759488a6d0
	public static Boolean CheckIfSameDIYInfo(IDictionary`2 lhs, IDictionary`2 rhs) { }
	// RVA: 0x2272a6c VA: 0x759488aa6c
	public static MedalGroupViewModel CreateMedalGroupModel4Display(String groupId) { }
	// RVA: 0x2272db4 VA: 0x759488adb4
	public static MedalGroupViewModel CreateMedalGroupModel4Display(FriendMedalTemplateGroupInfo info) { }
	// RVA: 0x2273044 VA: 0x759488b044
	public static MedalExpireStatus CheckMedalExpireStatus(Int64 targetTs, List`1 expireTimes) { }
	// RVA: 0x227319c VA: 0x759488b19c
	public static String GetMedalProgressDesc(Int32 value, Int32 target) { }
	// RVA: 0x22732d0 VA: 0x759488b2d0
	public Void .ctor() { }
	// RVA: 0x2273350 VA: 0x759488b350
	private static Void .cctor() { }
}
```