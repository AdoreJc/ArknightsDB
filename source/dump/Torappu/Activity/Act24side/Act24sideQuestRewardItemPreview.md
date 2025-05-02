# Act24sideQuestRewardItemPreview

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Transform _itemCardContainer`

- `Single _cardScaleFactor`

- `GameObject _completeTagGo`

- `GameObject _alreadyHaveTagGo`

- `CanvasGroup _itemAlphaHanlder`

- `Single _alreadyHaveAlpha`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_viewModel`

- `Boolean m_isInited`


## Methods

- `Void Render(StageRewardViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideQuestRewardItemPreview : MonoBehaviour, IHotfixable
{
	protected Transform _itemCardContainer; // 0x18
	protected Single _cardScaleFactor; // 0x20
	protected GameObject _completeTagGo; // 0x28
	protected GameObject _alreadyHaveTagGo; // 0x30
	private CanvasGroup _itemAlphaHanlder; // 0x38
	private Single _alreadyHaveAlpha; // 0x40
	protected UIItemCard m_itemCard; // 0x48
	protected UIItemViewModel m_viewModel; // 0x50
	protected Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32c1a94 VA: 0x75958d9a94
	protected virtual Void _InitIfNot() { }
	// RVA: 0x32c1c3c VA: 0x75958d9c3c
	public Void Render(StageRewardViewModel viewModel, Boolean isStageComplete) { }
	// RVA: 0x32c1d64 VA: 0x75958d9d64
	public Void .ctor() { }
}
```