# HomeSecretaryCardViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `BasicCharInfoModel m_basicInfo`

- `String <realName>k__BackingField`

- `String <nickName>k__BackingField`

- `String <skinId>k__BackingField`


## Properties

- `BasicCharInfoModel basicCharInfo`

- `Int32 chrInstId`

- `String charId`

- `String tmplId`

- `CharStarMarkState starMark`

- `ProfessionCategory profession`

- `String realName`

- `String nickName`

- `String skinId`


## Methods

- `BasicCharInfoModel get_basicCharInfo()`

- `Void set_basicCharInfo(BasicCharInfoModel)`

- `Int32 get_chrInstId()`

- `String get_charId()`

- `String get_tmplId()`

- `CharStarMarkState get_starMark()`

- `ProfessionCategory get_profession()`

- `String get_realName()`

- `Void set_realName(String)`

- `String get_nickName()`

- `Void set_nickName(String)`

- `String get_skinId()`

- `Void set_skinId(String)`

- `CharQuery GetCharQuery()`

- `Boolean FillViewModel(PlayerCharacter, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretaryCardViewModel : IBasicCharInfo, IHotfixable
{
	private BasicCharInfoModel m_basicInfo; // 0x10
	private String <realName>k__BackingField; // 0x18
	private String <nickName>k__BackingField; // 0x20
	private String <skinId>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_basicCharInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_basicCharInfo; // 0x8
	private static DelegateBridge __Hotfix0_get_chrInstId; // 0x10
	private static DelegateBridge __Hotfix0_get_charId; // 0x18
	private static DelegateBridge __Hotfix0_get_tmplId; // 0x20
	private static DelegateBridge __Hotfix0_get_starMark; // 0x28
	private static DelegateBridge __Hotfix0_get_profession; // 0x30
	private static DelegateBridge __Hotfix0_get_realName; // 0x38
	private static DelegateBridge __Hotfix0_set_realName; // 0x40
	private static DelegateBridge __Hotfix0_get_nickName; // 0x48
	private static DelegateBridge __Hotfix0_set_nickName; // 0x50
	private static DelegateBridge __Hotfix0_get_skinId; // 0x58
	private static DelegateBridge __Hotfix0_set_skinId; // 0x60
	private static DelegateBridge __Hotfix0_GetCharQuery; // 0x68
	private static DelegateBridge __Hotfix0_FillViewModel; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public BasicCharInfoModel basicCharInfo { get; set; }
	public Int32 chrInstId { get; }
	public String charId { get; }
	public String tmplId { get; }
	public CharStarMarkState starMark { get; }
	public ProfessionCategory profession { get; }
	public String realName { get; set; }
	public String nickName { get; set; }
	public String skinId { get; set; }

	// RVA: 0x2812130 VA: 0x7594e2a130
	public BasicCharInfoModel get_basicCharInfo() { }
	// RVA: 0x2812198 VA: 0x7594e2a198
	public Void set_basicCharInfo(BasicCharInfoModel value) { }
	// RVA: 0x281221c VA: 0x7594e2a21c
	public Int32 get_chrInstId() { }
	// RVA: 0x2812290 VA: 0x7594e2a290
	public String get_charId() { }
	// RVA: 0x2812304 VA: 0x7594e2a304
	public String get_tmplId() { }
	// RVA: 0x2812378 VA: 0x7594e2a378
	public CharStarMarkState get_starMark() { }
	// RVA: 0x28123ec VA: 0x7594e2a3ec
	public ProfessionCategory get_profession() { }
	// RVA: 0x2812460 VA: 0x7594e2a460
	public String get_realName() { }
	// RVA: 0x28124c8 VA: 0x7594e2a4c8
	private Void set_realName(String value) { }
	// RVA: 0x281254c VA: 0x7594e2a54c
	public String get_nickName() { }
	// RVA: 0x28125b4 VA: 0x7594e2a5b4
	private Void set_nickName(String value) { }
	// RVA: 0x2812638 VA: 0x7594e2a638
	public String get_skinId() { }
	// RVA: 0x28126a0 VA: 0x7594e2a6a0
	private Void set_skinId(String value) { }
	// RVA: 0x2812724 VA: 0x7594e2a724
	public CharQuery GetCharQuery() { }
	// RVA: 0x28127f4 VA: 0x7594e2a7f4
	public Boolean FillViewModel(PlayerCharacter playerChar, String overrideSkinId) { }
	// RVA: 0x2812a1c VA: 0x7594e2aa1c
	public Void .ctor() { }
}
```