# Act1VAutoChessChessShopQuickAssistItemViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <chessId>k__BackingField`

- `Act1VAutoChessShopCharChessCardViewModel <charCardViewModel>k__BackingField`

- `String <backUpCharId>k__BackingField`

- `Boolean <isAssisting>k__BackingField`

- `String <assistUid>k__BackingField`

- `String <assistNickName>k__BackingField`

- `String <assistNickNumber>k__BackingField`

- `String <assistAlias>k__BackingField`

- `Boolean <canAssistMore>k__BackingField`


## Properties

- `String chessId`

- `Act1VAutoChessShopCharChessCardViewModel charCardViewModel`

- `String backUpCharId`

- `Boolean isAssisting`

- `String assistUid`

- `String assistNickName`

- `String assistNickNumber`

- `String assistAlias`

- `Boolean canAssistMore`


## Methods

- `String get_chessId()`

- `Void set_chessId(String)`

- `Act1VAutoChessShopCharChessCardViewModel get_charCardViewModel()`

- `Void set_charCardViewModel(Act1VAutoChessShopCharChessCardViewModel)`

- `String get_backUpCharId()`

- `Void set_backUpCharId(String)`

- `Boolean get_isAssisting()`

- `Void set_isAssisting(Boolean)`

- `String get_assistUid()`

- `Void set_assistUid(String)`

- `String get_assistNickName()`

- `Void set_assistNickName(String)`

- `String get_assistNickNumber()`

- `Void set_assistNickNumber(String)`

- `String get_assistAlias()`

- `Void set_assistAlias(String)`

- `Boolean get_canAssistMore()`

- `Void set_canAssistMore(Boolean)`

- `Void LoadData(Act1VAutoChessShopCharChessCardViewModel, Act1VAutoChessCharShopChessData, Boolean, Dictionary`2)`

- `Void RefreshAssistCardInfoByPlayerData(Boolean, Dictionary`2)`

- `Void RefreshCanAssistMoreInfo(Boolean)`

- `Int32 CompareTo(Act1VAutoChessChessShopQuickAssistItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopQuickAssistItemViewModel : IHotfixable, IComparable`1
{
	private String <chessId>k__BackingField; // 0x10
	private Act1VAutoChessShopCharChessCardViewModel <charCardViewModel>k__BackingField; // 0x18
	private String <backUpCharId>k__BackingField; // 0x20
	private Boolean <isAssisting>k__BackingField; // 0x28
	private String <assistUid>k__BackingField; // 0x30
	private String <assistNickName>k__BackingField; // 0x38
	private String <assistNickNumber>k__BackingField; // 0x40
	private String <assistAlias>k__BackingField; // 0x48
	private Boolean <canAssistMore>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_chessId; // 0x0
	private static DelegateBridge __Hotfix0_set_chessId; // 0x8
	private static DelegateBridge __Hotfix0_get_charCardViewModel; // 0x10
	private static DelegateBridge __Hotfix0_set_charCardViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_backUpCharId; // 0x20
	private static DelegateBridge __Hotfix0_set_backUpCharId; // 0x28
	private static DelegateBridge __Hotfix0_get_isAssisting; // 0x30
	private static DelegateBridge __Hotfix0_set_isAssisting; // 0x38
	private static DelegateBridge __Hotfix0_get_assistUid; // 0x40
	private static DelegateBridge __Hotfix0_set_assistUid; // 0x48
	private static DelegateBridge __Hotfix0_get_assistNickName; // 0x50
	private static DelegateBridge __Hotfix0_set_assistNickName; // 0x58
	private static DelegateBridge __Hotfix0_get_assistNickNumber; // 0x60
	private static DelegateBridge __Hotfix0_set_assistNickNumber; // 0x68
	private static DelegateBridge __Hotfix0_get_assistAlias; // 0x70
	private static DelegateBridge __Hotfix0_set_assistAlias; // 0x78
	private static DelegateBridge __Hotfix0_get_canAssistMore; // 0x80
	private static DelegateBridge __Hotfix0_set_canAssistMore; // 0x88
	private static DelegateBridge __Hotfix0_LoadData; // 0x90
	private static DelegateBridge __Hotfix0_RefreshAssistCardInfoByPlayerData; // 0x98
	private static DelegateBridge __Hotfix0_RefreshCanAssistMoreInfo; // 0xa0
	private static DelegateBridge __Hotfix0_CompareTo; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public String chessId { get; set; }
	public Act1VAutoChessShopCharChessCardViewModel charCardViewModel { get; set; }
	public String backUpCharId { get; set; }
	public Boolean isAssisting { get; set; }
	public String assistUid { get; set; }
	public String assistNickName { get; set; }
	public String assistNickNumber { get; set; }
	public String assistAlias { get; set; }
	public Boolean canAssistMore { get; set; }

	// RVA: 0x331ec08 VA: 0x7595936c08
	public String get_chessId() { }
	// RVA: 0x3326058 VA: 0x759593e058
	private Void set_chessId(String value) { }
	// RVA: 0x331e978 VA: 0x7595936978
	public Act1VAutoChessShopCharChessCardViewModel get_charCardViewModel() { }
	// RVA: 0x33260dc VA: 0x759593e0dc
	public Void set_charCardViewModel(Act1VAutoChessShopCharChessCardViewModel value) { }
	// RVA: 0x331ec78 VA: 0x7595936c78
	public String get_backUpCharId() { }
	// RVA: 0x3326160 VA: 0x759593e160
	private Void set_backUpCharId(String value) { }
	// RVA: 0x331eb38 VA: 0x7595936b38
	public Boolean get_isAssisting() { }
	// RVA: 0x33261e4 VA: 0x759593e1e4
	private Void set_isAssisting(Boolean value) { }
	// RVA: 0x331ece0 VA: 0x7595936ce0
	public String get_assistUid() { }
	// RVA: 0x3326264 VA: 0x759593e264
	private Void set_assistUid(String value) { }
	// RVA: 0x331edb0 VA: 0x7595936db0
	public String get_assistNickName() { }
	// RVA: 0x33262e8 VA: 0x759593e2e8
	private Void set_assistNickName(String value) { }
	// RVA: 0x331ee18 VA: 0x7595936e18
	public String get_assistNickNumber() { }
	// RVA: 0x332636c VA: 0x759593e36c
	private Void set_assistNickNumber(String value) { }
	// RVA: 0x331ed48 VA: 0x7595936d48
	public String get_assistAlias() { }
	// RVA: 0x33263f0 VA: 0x759593e3f0
	private Void set_assistAlias(String value) { }
	// RVA: 0x331eba0 VA: 0x7595936ba0
	public Boolean get_canAssistMore() { }
	// RVA: 0x3326474 VA: 0x759593e474
	private Void set_canAssistMore(Boolean value) { }
	// RVA: 0x33264f4 VA: 0x759593e4f4
	public Void LoadData(Act1VAutoChessShopCharChessCardViewModel cardViewModel, Act1VAutoChessCharShopChessData shopChessData, Boolean canStillAssist, Dictionary`2 chessPlayerDataPool) { }
	// RVA: 0x33265e8 VA: 0x759593e5e8
	public Void RefreshAssistCardInfoByPlayerData(Boolean canStillAssist, Dictionary`2 chessPlayerDataPool) { }
	// RVA: 0x33267c4 VA: 0x759593e7c4
	public Void RefreshCanAssistMoreInfo(Boolean canStillAssist) { }
	// RVA: 0x3326844 VA: 0x759593e844
	public Int32 CompareTo(Act1VAutoChessChessShopQuickAssistItemViewModel other) { }
	// RVA: 0x3326928 VA: 0x759593e928
	public Void .ctor() { }
}
```