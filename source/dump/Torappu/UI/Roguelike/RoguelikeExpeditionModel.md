# RoguelikeExpeditionModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String <selectingCharInstId>k__BackingField`

- `String <defaultSelectDesc>k__BackingField`

- `String <topicId>k__BackingField`

- `Boolean isInit`

- `RoguelikeExpeditionCharListSort overrideCharListSort`


## Properties

- `String selectingCharInstId`

- `String defaultSelectDesc`

- `String topicId`

- `RoguelikeExpeditionCharCardViewModel selectingCharViewModel`


## Methods

- `String get_selectingCharInstId()`

- `Void set_selectingCharInstId(String)`

- `String get_defaultSelectDesc()`

- `Void set_defaultSelectDesc(String)`

- `String get_topicId()`

- `Void set_topicId(String)`

- `RoguelikeExpeditionCharCardViewModel get_selectingCharViewModel()`

- `Void LoadData(String)`

- `Boolean UpdateSelectingCharId(String)`

- `Int32 <LoadData>b__20_0(KeyValuePair`2, KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeExpeditionModel : IHotfixable
{
	public ListDict`2 expeditionChars; // 0x10
	private String <selectingCharInstId>k__BackingField; // 0x18
	private String <defaultSelectDesc>k__BackingField; // 0x20
	private String <topicId>k__BackingField; // 0x28
	public Boolean isInit; // 0x30
	public RoguelikeExpeditionCharListSort overrideCharListSort; // 0x38
	private List`1 m_charList; // 0x40
	private static DelegateBridge __Hotfix0_get_selectingCharInstId; // 0x0
	private static DelegateBridge __Hotfix0_set_selectingCharInstId; // 0x8
	private static DelegateBridge __Hotfix0_get_defaultSelectDesc; // 0x10
	private static DelegateBridge __Hotfix0_set_defaultSelectDesc; // 0x18
	private static DelegateBridge __Hotfix0_get_topicId; // 0x20
	private static DelegateBridge __Hotfix0_set_topicId; // 0x28
	private static DelegateBridge __Hotfix0_get_selectingCharViewModel; // 0x30
	private static DelegateBridge __Hotfix0_get_charList; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_UpdateSelectingCharId; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String selectingCharInstId { get; set; }
	public String defaultSelectDesc { get; set; }
	public String topicId { get; set; }
	public RoguelikeExpeditionCharCardViewModel selectingCharViewModel { get; }
	public List`1 charList { get; }

	// RVA: 0x2a32aa0 VA: 0x759504aaa0
	public String get_selectingCharInstId() { }
	// RVA: 0x2a32b08 VA: 0x759504ab08
	private Void set_selectingCharInstId(String value) { }
	// RVA: 0x2a32b8c VA: 0x759504ab8c
	public String get_defaultSelectDesc() { }
	// RVA: 0x2a32bf4 VA: 0x759504abf4
	private Void set_defaultSelectDesc(String value) { }
	// RVA: 0x2a32c78 VA: 0x759504ac78
	public String get_topicId() { }
	// RVA: 0x2a32ce0 VA: 0x759504ace0
	private Void set_topicId(String value) { }
	// RVA: 0x2a32d64 VA: 0x759504ad64
	public RoguelikeExpeditionCharCardViewModel get_selectingCharViewModel() { }
	// RVA: 0x2a32e1c VA: 0x759504ae1c
	public List`1 get_charList() { }
	// RVA: 0x2a33078 VA: 0x759504b078
	public Void LoadData(String topicId) { }
	// RVA: 0x2a33420 VA: 0x759504b420
	public Boolean UpdateSelectingCharId(String charInstId) { }
	// RVA: 0x2a33514 VA: 0x759504b514
	public Void .ctor() { }
	// RVA: 0x2a335d8 VA: 0x759504b5d8
	private Int32 <LoadData>b__20_0(KeyValuePair`2 l, KeyValuePair`2 r) { }
}
```