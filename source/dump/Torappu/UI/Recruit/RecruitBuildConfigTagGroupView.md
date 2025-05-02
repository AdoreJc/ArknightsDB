# RecruitBuildConfigTagGroupView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `UIIntEvent _tagClickEvent`

- `GameObject _emptyState`

- `GameObject _unFinishState`

- `GameObject _finishState`

- `RecruitBuildConfigTagView _tagPrefab`

- `Transform _tagContainer`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _RefreshTagState(Object)`

- `Void _OnTagClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildConfigTagGroupView : DataBinder`1
{
	private const Int32 TAG_COUNT; // 0x0
	private UIIntEvent _tagClickEvent; // 0x20
	private GameObject _emptyState; // 0x28
	private GameObject _unFinishState; // 0x30
	private GameObject _finishState; // 0x38
	private RecruitBuildConfigTagView _tagPrefab; // 0x40
	private Transform _tagContainer; // 0x48
	private RecruitBuildConfigTagView[] m_tagViews; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__RefreshTagState; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnTagClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x270de7c VA: 0x7594d25e7c
	private Void _InitIfNot() { }
	// RVA: 0x270e214 VA: 0x7594d26214
	private Void _RefreshTagState(Object obj) { }
	// RVA: 0x270e3ac VA: 0x7594d263ac
	public override Void OnValueChanged(BuildConfigTagGroupViewProperty property) { }
	// RVA: 0x270e73c VA: 0x7594d2673c
	private Void _OnTagClick(Int32 tagIndex) { }
	// RVA: 0x270e7e8 VA: 0x7594d267e8
	public Void .ctor() { }
}
```