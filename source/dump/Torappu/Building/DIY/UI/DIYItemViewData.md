# DIYItemViewData

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Int32 m_count`

- `Int32 m_totalCount`

- `Boolean m_isNew`

- `String m_invalidText`

- `Int32 m_funcTypePlacedCount`

- `Int32 m_inUseCount`

- `Int32 m_limitCount`

- `CountStatus m_countStatus`


## Methods

- `Int32 SetCount(Int32)`

- `Int32 GetCount()`

- `Int32 SetTotalCount(Int32)`

- `Int32 GetTotalCount()`

- `Int32 SetInUseCount(Int32)`

- `Int32 GetInUseCount()`

- `Int32 GetSubTypeLimitCount()`

- `Int32 SetFuncTypePlacedCount(Int32)`

- `Int32 GetFuncTypePlacedCount()`

- `Void SetCountStatus(CountStatus)`

- `CountStatus GetCountStatus()`

- `Void _OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYItemViewData : IHotfixable
{
	private Int32 m_count; // 0x10
	private Int32 m_totalCount; // 0x14
	private Boolean m_isNew; // 0x18
	private String m_invalidText; // 0x20
	private Int32 m_funcTypePlacedCount; // 0x28
	private Int32 m_inUseCount; // 0x2c
	private Int32 m_limitCount; // 0x30
	private CountStatus m_countStatus; // 0x34
	private static DelegateBridge __Hotfix0_GetBigSprite; // 0x0
	private static DelegateBridge __Hotfix0_GetSmallSprite; // 0x8
	private static DelegateBridge __Hotfix0_SetCount; // 0x10
	private static DelegateBridge __Hotfix0_GetCount; // 0x18
	private static DelegateBridge __Hotfix0_SetTotalCount; // 0x20
	private static DelegateBridge __Hotfix0_GetTotalCount; // 0x28
	private static DelegateBridge __Hotfix0_SetInUseCount; // 0x30
	private static DelegateBridge __Hotfix0_GetInUseCount; // 0x38
	private static DelegateBridge __Hotfix0_GetSubTypeLimitCount; // 0x40
	private static DelegateBridge __Hotfix0_SetFuncTypePlacedCount; // 0x48
	private static DelegateBridge __Hotfix0_GetFuncTypePlacedCount; // 0x50
	private static DelegateBridge __Hotfix0_SetCountStatus; // 0x58
	private static DelegateBridge __Hotfix0_GetCountStatus; // 0x60
	private static DelegateBridge __Hotfix0_get_diyItem; // 0x68
	private static DelegateBridge __Hotfix0_get_enableRoomType; // 0x70
	private static DelegateBridge __Hotfix0_get_furnitureType; // 0x78
	private static DelegateBridge __Hotfix0_get_subType; // 0x80
	private static DelegateBridge __Hotfix0_ShowCount; // 0x88
	private static DelegateBridge __Hotfix0_ShowCurrentCount; // 0x90
	private static DelegateBridge __Hotfix0_ShowTotalCount; // 0x98
	private static DelegateBridge __Hotfix0_ShowSubButton; // 0xa0
	private static DelegateBridge __Hotfix0_SetShowTotalCount; // 0xa8
	private static DelegateBridge __Hotfix0_ShowRenameButton; // 0xb0
	private static DelegateBridge __Hotfix0_IsCountLabelAtCorner; // 0xb8
	private static DelegateBridge __Hotfix0_ShowComfort; // 0xc0
	private static DelegateBridge __Hotfix0_GetComfort; // 0xc8
	private static DelegateBridge __Hotfix0_SetComfort; // 0xd0
	private static DelegateBridge __Hotfix0_SetShowComfort; // 0xd8
	private static DelegateBridge __Hotfix0_ButtonValid; // 0xe0
	private static DelegateBridge __Hotfix0_GetDisplayName; // 0xe8
	private static DelegateBridge __Hotfix0_GetRarity; // 0xf0
	private static DelegateBridge __Hotfix0_GetTarget; // 0xf8
	private static DelegateBridge __Hotfix0_Uninitialize; // 0x100
	private static DelegateBridge __Hotfix0_Selected; // 0x108
	private static DelegateBridge __Hotfix0_ShowUpperInfoButton; // 0x110
	private static DelegateBridge __Hotfix0_ShowLowerInfoButton; // 0x118
	private static DelegateBridge __Hotfix0_GetIsNew; // 0x120
	private static DelegateBridge __Hotfix0_SetIsNew; // 0x128
	private static DelegateBridge __Hotfix0_GetInvalidText; // 0x130
	private static DelegateBridge __Hotfix0_SetInvalidText; // 0x138
	private static DelegateBridge __Hotfix0__OnInit; // 0x140
	private static DelegateBridge __Hotfix0_Create; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public virtual IDIYItem diyItem { get; }
	public virtual Int32 enableRoomType { get; }
	public virtual FurnitureType furnitureType { get; }
	public virtual FurnitureSubType subType { get; }

	// RVA: 0x381fab4 VA: 0x7595e37ab4
	public virtual Sprite GetBigSprite() { }
	// RVA: 0x381fb18 VA: 0x7595e37b18
	public virtual Sprite GetSmallSprite() { }
	// RVA: 0x381fb7c VA: 0x7595e37b7c
	public Int32 SetCount(Int32 count) { }
	// RVA: 0x381fbfc VA: 0x7595e37bfc
	public Int32 GetCount() { }
	// RVA: 0x381fc64 VA: 0x7595e37c64
	public Int32 SetTotalCount(Int32 totalCount) { }
	// RVA: 0x381fce4 VA: 0x7595e37ce4
	public Int32 GetTotalCount() { }
	// RVA: 0x381fd4c VA: 0x7595e37d4c
	public Int32 SetInUseCount(Int32 inUseCount) { }
	// RVA: 0x381fdcc VA: 0x7595e37dcc
	public Int32 GetInUseCount() { }
	// RVA: 0x381fe34 VA: 0x7595e37e34
	public Int32 GetSubTypeLimitCount() { }
	// RVA: 0x381fe9c VA: 0x7595e37e9c
	public Int32 SetFuncTypePlacedCount(Int32 count) { }
	// RVA: 0x381ff1c VA: 0x7595e37f1c
	public Int32 GetFuncTypePlacedCount() { }
	// RVA: 0x381ff84 VA: 0x7595e37f84
	public Void SetCountStatus(CountStatus status) { }
	// RVA: 0x3820000 VA: 0x7595e38000
	public CountStatus GetCountStatus() { }
	// RVA: 0x3820068 VA: 0x7595e38068
	public virtual IDIYItem get_diyItem() { }
	// RVA: 0x38200cc VA: 0x7595e380cc
	public virtual Int32 get_enableRoomType() { }
	// RVA: 0x3820134 VA: 0x7595e38134
	public virtual FurnitureType get_furnitureType() { }
	// RVA: 0x3820198 VA: 0x7595e38198
	public virtual FurnitureSubType get_subType() { }
	// RVA: 0x38201fc VA: 0x7595e381fc
	public virtual Boolean ShowCount() { }
	// RVA: 0x3820264 VA: 0x7595e38264
	public virtual Boolean ShowCurrentCount() { }
	// RVA: 0x38202cc VA: 0x7595e382cc
	public virtual Boolean ShowTotalCount() { }
	// RVA: 0x3820334 VA: 0x7595e38334
	public virtual Boolean ShowSubButton() { }
	// RVA: 0x3820398 VA: 0x7595e38398
	public virtual Void SetShowTotalCount(Boolean showTotalCount) { }
	// RVA: 0x3820410 VA: 0x7595e38410
	public virtual Boolean ShowRenameButton() { }
	// RVA: 0x3820474 VA: 0x7595e38474
	public virtual Boolean IsCountLabelAtCorner() { }
	// RVA: 0x38204dc VA: 0x7595e384dc
	public virtual Boolean ShowComfort() { }
	// RVA: 0x3820540 VA: 0x7595e38540
	public virtual Int32 GetComfort() { }
	// RVA: 0x38205a4 VA: 0x7595e385a4
	public virtual Void SetComfort(Int32 comfort) { }
	// RVA: 0x382061c VA: 0x7595e3861c
	public virtual Void SetShowComfort(Boolean showComfort) { }
	// RVA: 0x3820694 VA: 0x7595e38694
	public virtual Boolean ButtonValid() { }
	// RVA: 0x38206fc VA: 0x7595e386fc
	public virtual String GetDisplayName() { }
	// RVA: 0x3820778 VA: 0x7595e38778
	public virtual Int32 GetRarity() { }
	// RVA: 0x38207dc VA: 0x7595e387dc
	public virtual Object GetTarget() { }
	// RVA: 0x3820840 VA: 0x7595e38840
	public virtual Void Uninitialize() { }
	// RVA: 0x38208a4 VA: 0x7595e388a4
	public virtual Boolean Selected() { }
	// RVA: 0x3820908 VA: 0x7595e38908
	public virtual Boolean ShowUpperInfoButton() { }
	// RVA: 0x382096c VA: 0x7595e3896c
	public virtual Boolean ShowLowerInfoButton() { }
	// RVA: 0x38209d0 VA: 0x7595e389d0
	public virtual Boolean GetIsNew() { }
	// RVA: 0x3820a38 VA: 0x7595e38a38
	public virtual Void SetIsNew(Boolean isNew) { }
	// RVA: 0x3820ab8 VA: 0x7595e38ab8
	public virtual String GetInvalidText() { }
	// RVA: 0x3820b20 VA: 0x7595e38b20
	public virtual Void SetInvalidText(String invalidText) { }
	// RVA: 0x3820ba4 VA: 0x7595e38ba4
	private Void _OnInit() { }
	// RVA: 0x3820c54 VA: 0x7595e38c54
	public static DIYItemViewData Create(Object target) { }
	// RVA: 0x3820efc VA: 0x7595e38efc
	public Void .ctor() { }
}
```