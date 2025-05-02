# CharacterRepoPage

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `LoopScrollRect _scrollRectToStop`

- `GameObject _cardGroupPage`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`


## Methods

- `Void EventOnFilterClick()`

- `Void EventOnSortTypeClick(CharacterSortType)`

- `Void EventOnTrackPointFilterClick()`

- `Void EventOnStarMarkTopClick()`

- `Void EventOnCharacterCardClick(Int32)`

- `Boolean _CheckJumpToHandBookStage(CharacterRepoStateBean, Int32)`

- `DataBundle _GenJumpToHandBookStageBundle(String, List`1)`

- `Void _OnInitTopMenu(GameObject)`

- `Void _ShowCharacterInfo(Int32, List`1)`

- `Void _ShowCharacterHandbookStageInfo(String, List`1)`

- `IEnumerator <>n__0(Boolean)`

- `Void <_OnInitTopMenu>b__16_0()`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`

- `Boolean <>xLuaBaseProxy_CustomSetActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class CharacterRepoPage : StateEnginePage, IHotfixable
{
	private LoopScrollRect _scrollRectToStop; // 0xe8
	private GameObject _cardGroupPage; // 0xf0
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xf8
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x0
	private static DelegateBridge __Hotfix0_OnStart; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x18
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x20
	private static DelegateBridge __Hotfix0_EventOnFilterClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnSortTypeClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnTrackPointFilterClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnStarMarkTopClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnCharacterCardClick; // 0x48
	private static DelegateBridge __Hotfix0__CheckJumpToHandBookStage; // 0x50
	private static DelegateBridge __Hotfix0__GenJumpToHandBookStageBundle; // 0x58
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x60
	private static DelegateBridge __Hotfix0__ShowCharacterInfo; // 0x68
	private static DelegateBridge __Hotfix0__ShowCharacterHandbookStageInfo; // 0x70
	private static DelegateBridge __Hotfix0__EnumAllPlayerCharIds; // 0x78
	private static DelegateBridge __Hotfix0__TraceForCharsViewed; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public override AVGPageKey avgPage { get; }

	// RVA: 0x2cf7b38 VA: 0x759530fb38
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x2cf7ba0 VA: 0x759530fba0
	protected override Void OnStart() { }
	// RVA: 0x2cf811c VA: 0x759531011c
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2cf8204 VA: 0x7595310204
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x2cf82f4 VA: 0x75953102f4
	public override Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x2cf8440 VA: 0x7595310440
	public Void EventOnFilterClick() { }
	// RVA: 0x2cf853c VA: 0x759531053c
	public Void EventOnSortTypeClick(CharacterSortType sortType) { }
	// RVA: 0x2cf86b0 VA: 0x75953106b0
	public Void EventOnTrackPointFilterClick() { }
	// RVA: 0x2cf87f0 VA: 0x75953107f0
	public Void EventOnStarMarkTopClick() { }
	// RVA: 0x2cf8930 VA: 0x7595310930
	public Void EventOnCharacterCardClick(Int32 chrInstId) { }
	// RVA: 0x2cf8b74 VA: 0x7595310b74
	private Boolean _CheckJumpToHandBookStage(CharacterRepoStateBean stateBean, Int32 chrInstId) { }
	// RVA: 0x2cf914c VA: 0x759531114c
	private DataBundle _GenJumpToHandBookStageBundle(String charId, List`1 charList) { }
	// RVA: 0x2cf9254 VA: 0x7595311254
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2cf8f44 VA: 0x7595310f44
	private Void _ShowCharacterInfo(Int32 charInstId, List`1 charList) { }
	// RVA: 0x2cf8e4c VA: 0x7595310e4c
	private Void _ShowCharacterHandbookStageInfo(String charId, List`1 charList) { }
	// RVA: 0x2cf939c VA: 0x759531139c
	private static IEnumerator`1 _EnumAllPlayerCharIds() { }
	// RVA: 0x2cf9458 VA: 0x7595311458
	private static IEnumerator`1 _TraceForCharsViewed() { }
	// RVA: 0x2cf9514 VA: 0x7595311514
	public Void .ctor() { }
	// RVA: 0x2cf9584 VA: 0x7595311584
	private IEnumerator <>n__0(Boolean isIntoStack) { }
	// RVA: 0x2cf9590 VA: 0x7595311590
	private Void <_OnInitTopMenu>b__16_0() { }
	// RVA: 0x2cf968c VA: 0x759531168c
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x2cf9694 VA: 0x7595311694
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2cf969c VA: 0x759531169c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2cf96a4 VA: 0x75953116a4
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
	// RVA: 0x2cf96b0 VA: 0x75953116b0
	private Boolean <>xLuaBaseProxy_CustomSetActive(Boolean P0) { }
}
```