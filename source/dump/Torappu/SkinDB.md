# SkinDB

**Namespace:** `Torappu`


## Methods

- `Boolean TryGetSkinListByCharId(String, out)`

- `Boolean TryGetCharSkin(String, out)`

- `Boolean ContainsCharSkin(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SkinDB : ConstTable`2
{
	public static readonly HashSet`1 BASIC_CHAR_ARTS; // 0x0
	public const String BASIC_ILLUST_CHAR; // 0x0
	public const String BASIC_ILLUST_ID; // 0x0
	private static ListSet`1 s_sharedSet; // 0x8
	private Dictionary`2 m_charIdSkinMap; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_TryGetSkinListByCharId; // 0x18
	private static DelegateBridge __Hotfix0_TryGetCharSkin; // 0x20
	private static DelegateBridge __Hotfix0_ContainsCharSkin; // 0x28
	private static DelegateBridge __Hotfix0_TryPickBestBuildinSkinId; // 0x30
	private static DelegateBridge __Hotfix0__TryPickPatchSkin; // 0x38
	private static DelegateBridge __Hotfix0_TryGetEvolveSkin; // 0x40
	private static DelegateBridge __Hotfix0_TryGetNPCSkin; // 0x48
	private static DelegateBridge __Hotfix0_GetSelectableSkinsWithPatch; // 0x50
	private static DelegateBridge __Hotfix0_AuditOnlyHookBasicSkin; // 0x58
	private static DelegateBridge __Hotfix0__FlushSkinsToDefault; // 0x60
	private static DelegateBridge __Hotfix0__RevertToDefaultIfNecessary; // 0x68
	private static DelegateBridge __Hotfix0__CheckIfBasicThinMode; // 0x70
	private static DelegateBridge __Hotfix0_EditorGetAllNonDefaultSkinList; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x31f79ec VA: 0x759580f9ec
	protected override Void OnInit() { }
	// RVA: 0x31f83b0 VA: 0x75958103b0
	public Boolean TryGetSkinListByCharId(String charId, out List`1 skinList) { }
	// RVA: 0x31f84a0 VA: 0x75958104a0
	public Boolean TryGetCharSkin(String skinId, out CharSkinData skin) { }
	// RVA: 0x31f85b0 VA: 0x75958105b0
	public Boolean ContainsCharSkin(String skinId) { }
	// RVA: 0x31f86a4 VA: 0x75958106a4
	public static Boolean TryPickBestBuildinSkinId(CharQuery charQuery, EvolvePhase evolvePhase, out String skinId) { }
	// RVA: 0x31f88ec VA: 0x75958108ec
	private static Boolean _TryPickPatchSkin(String charId, String tmplId, out String skinId) { }
	// RVA: 0x31f8a40 VA: 0x7595810a40
	public static Boolean TryGetEvolveSkin(String charId, EvolvePhase evolvePhase, out String skinId) { }
	// RVA: 0x31f8b98 VA: 0x7595810b98
	public static Boolean TryGetNPCSkin(String npcId, out String skinId) { }
	// RVA: 0x31f8d2c VA: 0x7595810d2c
	public static ListSet`1 GetSelectableSkinsWithPatch(PlayerCharacter playerChar) { }
	// RVA: 0x31f912c VA: 0x759581112c
	public static Void AuditOnlyHookBasicSkin(ref CharQuery charQuery, ref String illustId) { }
	// RVA: 0x31f7f58 VA: 0x759580ff58
	private static Void _FlushSkinsToDefault(SkinTable skinTable) { }
	// RVA: 0x31f92e4 VA: 0x75958112e4
	private static String _RevertToDefaultIfNecessary(String charId, String skinId, SkinTable skinTable) { }
	// RVA: 0x31f926c VA: 0x759581126c
	private static Boolean _CheckIfBasicThinMode() { }
	// RVA: 0x31f9458 VA: 0x7595811458
	public static List`1 EditorGetAllNonDefaultSkinList() { }
	// RVA: 0x31f9668 VA: 0x7595811668
	public Void .ctor() { }
	// RVA: 0x31f975c VA: 0x759581175c
	private static Void .cctor() { }
}
```