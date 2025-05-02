# RL03TotemBuffView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RL03TotemBuffMapView _mapView`

- `RL03TotemBuffListView _listView`

- `RL03TotemBuffBottomView _bottomView`

- `RectTransform _rectTransformBack`

- `UIAnimationLocation _entryAnimLocation`

- `RL03TotemBuffViewModel m_viewModel`

- `State m_bindState`

- `Tween m_entryTween`


## Methods

- `Void EventOnBackClick()`

- `Void _OnBackPressed()`

- `Void _PlayEntryAnim()`

- `Void _OnTotemListItemClick(String, String)`

- `Void _OnMapNodeClick(Int32, Int32)`

- `Void _OnConfirmBtnClick()`

- `Void _SendUseTotemRequest(List`1, List`1, Action)`

- `Void _OnUseTotemRequestCompleted()`

- `Void _OnUseTotemDialogCompleted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffView : AbstractRoguelikeTotemBuffView
{
	private RL03TotemBuffMapView _mapView; // 0x18
	private RL03TotemBuffListView _listView; // 0x20
	private RL03TotemBuffBottomView _bottomView; // 0x28
	private RectTransform _rectTransformBack; // 0x30
	private UIAnimationLocation _entryAnimLocation; // 0x38
	private RL03TotemBuffViewModel m_viewModel; // 0x48
	private State m_bindState; // 0x50
	private Tween m_entryTween; // 0x58
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_BindState; // 0x8
	private static DelegateBridge __Hotfix0_OnStateResume; // 0x10
	private static DelegateBridge __Hotfix0_GeneViewData; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBackClick; // 0x20
	private static DelegateBridge __Hotfix0__OnBackPressed; // 0x28
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x30
	private static DelegateBridge __Hotfix0__OnTotemListItemClick; // 0x38
	private static DelegateBridge __Hotfix0__OnMapNodeClick; // 0x40
	private static DelegateBridge __Hotfix0__OnConfirmBtnClick; // 0x48
	private static DelegateBridge __Hotfix0__SendUseTotemRequest; // 0x50
	private static DelegateBridge __Hotfix0__OnUseTotemRequestCompleted; // 0x58
	private static DelegateBridge __Hotfix0__OnUseTotemDialogCompleted; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2babf50 VA: 0x75951c3f50
	public override Void OnInit() { }
	// RVA: 0x2bac35c VA: 0x75951c435c
	public override Void BindState(State state) { }
	// RVA: 0x2bac3e0 VA: 0x75951c43e0
	public override Void OnStateResume() { }
	// RVA: 0x2bac468 VA: 0x75951c4468
	public override IRoguelikeTotemBuffViewModel GeneViewData(String topicId, Boolean isOpenDirectFromDungeon) { }
	// RVA: 0x2bac700 VA: 0x75951c4700
	public Void EventOnBackClick() { }
	// RVA: 0x2bac7c4 VA: 0x75951c47c4
	private Void _OnBackPressed() { }
	// RVA: 0x2bac1ec VA: 0x75951c41ec
	private Void _PlayEntryAnim() { }
	// RVA: 0x2bac888 VA: 0x75951c4888
	private Void _OnTotemListItemClick(String totemId, String instId) { }
	// RVA: 0x2baccd4 VA: 0x75951c4cd4
	private Void _OnMapNodeClick(Int32 depth, Int32 index) { }
	// RVA: 0x2baceb8 VA: 0x75951c4eb8
	private Void _OnConfirmBtnClick() { }
	// RVA: 0x2bad2fc VA: 0x75951c52fc
	private Void _SendUseTotemRequest(List`1 totemIndex, List`1 nodeIndex, Action requestCallback) { }
	// RVA: 0x2bad574 VA: 0x75951c5574
	private Void _OnUseTotemRequestCompleted() { }
	// RVA: 0x2bad7d8 VA: 0x75951c57d8
	private Void _OnUseTotemDialogCompleted() { }
	// RVA: 0x2bad8ec VA: 0x75951c58ec
	public Void .ctor() { }
}
```