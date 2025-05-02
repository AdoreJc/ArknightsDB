# UISquadEditCharModel

**Namespace:** `Torappu.UI`


## Fields

- `Int32 <charInstId>k__BackingField`

- `String <charId>k__BackingField`

- `Int32 m_skillIndex`

- `String m_equipId`

- `String m_defaultEquipId`

- `String m_curTmpl`


## Properties

- `Int32 charInstId`

- `String charId`

- `String currentTmpl`


## Methods

- `Int32 get_charInstId()`

- `Void set_charInstId(Int32)`

- `String get_charId()`

- `Void set_charId(String)`

- `Patch _SafeTmpl(String)`

- `Int32 GetSkillIndex(String)`

- `String GetDefaultEquipId()`

- `String GetEquipId(String)`

- `CharQuery GetCharQuery()`

- `String get_currentTmpl()`

- `Int32 GetSkillIndex()`

- `Void SetSkillIndex(Int32)`

- `String GetEquipId()`

- `Void SetEquipId(String, String)`

- `Boolean SetTmpl(String)`

- `Int32 ExtraTmplCount()`

- `Void ApplyFriendViewModelFromPlayerChar(Int32, String, String, ISquadMemberCompInfo)`

- `Void ApplyFromCharCardModel(CharacterCardViewModel, String, String, ISquadMemberCompInfo)`

- `Void _ApplyImpl(Int32, CharQuery, Int32, String, String, IEnumerator`1)`

- `RequestAssistChar CreateRequestAssistChar()`

- `Int32 InternalSkillIndex()`

- `String InternalEquipId()`

- `String InternalDefaultEquipId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISquadEditCharModel : ISquadMemberCompInfo, IHotfixable
{
	private Int32 <charInstId>k__BackingField; // 0x10
	private String <charId>k__BackingField; // 0x18
	private Int32 m_skillIndex; // 0x20
	private String m_equipId; // 0x28
	private String m_defaultEquipId; // 0x30
	private String m_curTmpl; // 0x38
	private ListDict`2 m_tmpls; // 0x40
	private static DelegateBridge __Hotfix0_get_charInstId; // 0x0
	private static DelegateBridge __Hotfix0_set_charInstId; // 0x8
	private static DelegateBridge __Hotfix0_get_charId; // 0x10
	private static DelegateBridge __Hotfix0_set_charId; // 0x18
	private static DelegateBridge __Hotfix0__SafeTmpl; // 0x20
	private static DelegateBridge __Hotfix0_GetSkillIndex; // 0x28
	private static DelegateBridge __Hotfix0_GetDefaultEquipId; // 0x30
	private static DelegateBridge __Hotfix0_GetEquipId; // 0x38
	private static DelegateBridge __Hotfix0_GetCharQuery; // 0x40
	private static DelegateBridge __Hotfix0_get_currentTmpl; // 0x48
	private static DelegateBridge __Hotfix1_GetSkillIndex; // 0x50
	private static DelegateBridge __Hotfix0_SetSkillIndex; // 0x58
	private static DelegateBridge __Hotfix1_GetEquipId; // 0x60
	private static DelegateBridge __Hotfix0_SetEquipId; // 0x68
	private static DelegateBridge __Hotfix0_SetTmpl; // 0x70
	private static DelegateBridge __Hotfix0_ExtraTmplInfo; // 0x78
	private static DelegateBridge __Hotfix0_ExtraTmplCount; // 0x80
	private static DelegateBridge __Hotfix0_ApplyFriendViewModelFromPlayerChar; // 0x88
	private static DelegateBridge __Hotfix0_ApplyFromCharCardModel; // 0x90
	private static DelegateBridge __Hotfix0__CreateFromSquadProto; // 0x98
	private static DelegateBridge __Hotfix0__ApplyImpl; // 0xa0
	private static DelegateBridge __Hotfix0_CreateRequestAssistChar; // 0xa8
	private static DelegateBridge __Hotfix0_CreateFromPlayerAssists; // 0xb0
	private static DelegateBridge __Hotfix0_SyncFromPlayerData; // 0xb8
	private static DelegateBridge __Hotfix0_InternalSkillIndex; // 0xc0
	private static DelegateBridge __Hotfix0_InternalEquipId; // 0xc8
	private static DelegateBridge __Hotfix0_InternalDefaultEquipId; // 0xd0
	private static DelegateBridge __Hotfix0_InternalTmpls; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	public Int32 charInstId { get; set; }
	public String charId { get; set; }
	public String currentTmpl { get; }

	// RVA: 0x21e6fb8 VA: 0x75947fefb8
	public Int32 get_charInstId() { }
	// RVA: 0x21e7020 VA: 0x75947ff020
	private Void set_charInstId(Int32 value) { }
	// RVA: 0x21e709c VA: 0x75947ff09c
	public String get_charId() { }
	// RVA: 0x21e7104 VA: 0x75947ff104
	private Void set_charId(String value) { }
	// RVA: 0x21e7188 VA: 0x75947ff188
	private Patch _SafeTmpl(String tmplId) { }
	// RVA: 0x21e7248 VA: 0x75947ff248
	public Int32 GetSkillIndex(String tmplId) { }
	// RVA: 0x21e7304 VA: 0x75947ff304
	public String GetDefaultEquipId() { }
	// RVA: 0x21e73ac VA: 0x75947ff3ac
	public String GetEquipId(String tmplId) { }
	// RVA: 0x21e7468 VA: 0x75947ff468
	public CharQuery GetCharQuery() { }
	// RVA: 0x21e7530 VA: 0x75947ff530
	public String get_currentTmpl() { }
	// RVA: 0x21e7598 VA: 0x75947ff598
	public Int32 GetSkillIndex() { }
	// RVA: 0x21e7618 VA: 0x75947ff618
	public Void SetSkillIndex(Int32 index) { }
	// RVA: 0x21e76ac VA: 0x75947ff6ac
	public String GetEquipId() { }
	// RVA: 0x21e772c VA: 0x75947ff72c
	public Void SetEquipId(String i_equipId, String defaultEquipId) { }
	// RVA: 0x21e77f4 VA: 0x75947ff7f4
	public Boolean SetTmpl(String tmplId) { }
	// RVA: 0x21e7894 VA: 0x75947ff894
	public IEnumerator`1 ExtraTmplInfo() { }
	// RVA: 0x21e7968 VA: 0x75947ff968
	public Int32 ExtraTmplCount() { }
	// RVA: 0x21e79e8 VA: 0x75947ff9e8
	public Void ApplyFriendViewModelFromPlayerChar(Int32 instId, String skillId, String equipId, ISquadMemberCompInfo extraTmplInfo) { }
	// RVA: 0x21e80d0 VA: 0x75948000d0
	public Void ApplyFromCharCardModel(CharacterCardViewModel cardModel, String skillId, String equipId, ISquadMemberCompInfo extraTmplInfo) { }
	// RVA: 0x21e82a4 VA: 0x75948002a4
	private static UISquadEditCharModel _CreateFromSquadProto(PlayerSquadMemberProto proto) { }
	// RVA: 0x21e7c80 VA: 0x75947ffc80
	private Void _ApplyImpl(Int32 instId, CharQuery query, Int32 skillIndex, String equipId, String defaultEquipId, IEnumerator`1 extraTmpls) { }
	// RVA: 0x21e8528 VA: 0x7594800528
	public RequestAssistChar CreateRequestAssistChar() { }
	// RVA: 0x21e878c VA: 0x759480078c
	public static UISquadEditCharModel[] CreateFromPlayerAssists(IList`1 assists) { }
	// RVA: 0x21e89e4 VA: 0x75948009e4
	public static Boolean SyncFromPlayerData(IList`1 squad, out Boolean tmplChange) { }
	// RVA: 0x21e8ec8 VA: 0x7594800ec8
	public Int32 InternalSkillIndex() { }
	// RVA: 0x21e8f30 VA: 0x7594800f30
	public String InternalEquipId() { }
	// RVA: 0x21e8f98 VA: 0x7594800f98
	public String InternalDefaultEquipId() { }
	// RVA: 0x21e8e60 VA: 0x7594800e60
	public IDictionary`2 InternalTmpls() { }
	// RVA: 0x21e84b0 VA: 0x75948004b0
	public Void .ctor() { }
}
```