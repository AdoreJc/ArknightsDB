# FireworkPlateFilledListView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `SimpleLayoutContent _filledPlateList`

- `UIAnimationLocation _clearAllShowAnim`

- `Text _textFilledNum`

- `GameObject _tutorialGo`

- `Adapter m_adapter`

- `FireworkPlateGroupViewStyle m_cachedStyle`

- `Boolean m_inited`

- `UISwitchTween m_clearAllShowTween`

- `UIStateFinder m_stateFinder`

- `FireworkPlateGroupModel m_cachedGroupModel`


## Methods

- `Void _InitIfNot()`

- `Void Render(FireworkPlateGroupModel, FireworkPlateGroupViewStyle)`

- `Void RegisterTutorialGo()`

- `Void OnBtnClearAllClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateFilledListView : MonoBehaviour, IHotfixable
{
	private const String FILLED_NUM_FORMAT; // 0x0
	private SimpleLayoutContent _filledPlateList; // 0x18
	private UIAnimationLocation _clearAllShowAnim; // 0x20
	private Text _textFilledNum; // 0x30
	private GameObject _tutorialGo; // 0x38
	private Adapter m_adapter; // 0x40
	private FireworkPlateGroupViewStyle m_cachedStyle; // 0x48
	private Boolean m_inited; // 0x50
	private UISwitchTween m_clearAllShowTween; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private FireworkPlateGroupModel m_cachedGroupModel; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnClearAllClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28ece20 VA: 0x7594f04e20
	private Void _InitIfNot() { }
	// RVA: 0x28ecff8 VA: 0x7594f04ff8
	public Void Render(FireworkPlateGroupModel groupModel, FireworkPlateGroupViewStyle style) { }
	// RVA: 0x28ed2bc VA: 0x7594f052bc
	public Void RegisterTutorialGo() { }
	// RVA: 0x28ed388 VA: 0x7594f05388
	public Void OnBtnClearAllClicked() { }
	// RVA: 0x28ed43c VA: 0x7594f0543c
	public Void .ctor() { }
}
```