# CrisisV2SettleCommentItemViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String <comment>k__BackingField`

- `Boolean <isNew>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `String m_id`


## Properties

- `String comment`

- `Boolean isNew`

- `Int32 sortId`


## Methods

- `String get_comment()`

- `Void set_comment(String)`

- `Boolean get_isNew()`

- `Void set_isNew(Boolean)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Void LoadData(CrisisV2CommentData, Boolean)`

- `Void LoadData(CrisisV2AchievementCommentViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SettleCommentItemViewModel : IHotfixable
{
	private String <comment>k__BackingField; // 0x10
	private Boolean <isNew>k__BackingField; // 0x18
	private Int32 <sortId>k__BackingField; // 0x1c
	private String m_id; // 0x20
	private static DelegateBridge __Hotfix0_get_comment; // 0x0
	private static DelegateBridge __Hotfix0_set_comment; // 0x8
	private static DelegateBridge __Hotfix0_get_isNew; // 0x10
	private static DelegateBridge __Hotfix0_set_isNew; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_set_sortId; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix1_LoadData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String comment { get; set; }
	public Boolean isNew { get; set; }
	public Int32 sortId { get; set; }

	// RVA: 0x2bd0808 VA: 0x75951e8808
	public String get_comment() { }
	// RVA: 0x2bd5774 VA: 0x75951ed774
	private Void set_comment(String value) { }
	// RVA: 0x2bd0870 VA: 0x75951e8870
	public Boolean get_isNew() { }
	// RVA: 0x2bd57f8 VA: 0x75951ed7f8
	private Void set_isNew(Boolean value) { }
	// RVA: 0x2bd4eec VA: 0x75951eceec
	public Int32 get_sortId() { }
	// RVA: 0x2bd5878 VA: 0x75951ed878
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2bd58f4 VA: 0x75951ed8f4
	public Void LoadData(CrisisV2CommentData data, Boolean newGet) { }
	// RVA: 0x2bd59b8 VA: 0x75951ed9b8
	public Void LoadData(CrisisV2AchievementCommentViewModel model) { }
	// RVA: 0x2bd5a74 VA: 0x75951eda74
	public Void .ctor() { }
}
```