# ActMultiV3StageListTabView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `CanvasGroup _pnlSelected`

- `Text _textDiffName`

- `ActMultiV3MapDiffType _diffType`

- `CanvasGroup _canvasRaycast`

- `UIStateFinder m_stateFinder`

- `UISwitchTween m_tabSelectSwitchTween`

- `Boolean m_inited`

- `Int32 m_cachedLoadDataSeqNum`


## Methods

- `Void _InitIfNot()`

- `Void Render(ActMultiV3StageListViewModel)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListTabView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _pnlSelected; // 0x18
	private Text _textDiffName; // 0x20
	private ActMultiV3MapDiffType _diffType; // 0x28
	private CanvasGroup _canvasRaycast; // 0x30
	private UIStateFinder m_stateFinder; // 0x38
	private UISwitchTween m_tabSelectSwitchTween; // 0x48
	private Boolean m_inited; // 0x50
	private Int32 m_cachedLoadDataSeqNum; // 0x54
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x314f3e0 VA: 0x75957673e0
	private Void _InitIfNot() { }
	// RVA: 0x314f4c4 VA: 0x75957674c4
	public Void Render(ActMultiV3StageListViewModel model) { }
	// RVA: 0x314f714 VA: 0x7595767714
	public Void OnClicked() { }
	// RVA: 0x314f81c VA: 0x759576781c
	public Void .ctor() { }
}
```