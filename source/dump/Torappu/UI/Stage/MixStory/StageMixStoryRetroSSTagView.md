# StageMixStoryRetroSSTagView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `SimpleLayoutContent _tagContent`

- `LayoutGroup _tagLayout`

- `RectTransform _tagViewport`

- `CanvasGroup _defaultLayer`

- `CanvasGroup _expandedLayer`

- `Single _switchDuration`

- `Ease _switchEase`

- `Boolean m_hasInited`

- `UIPageFinder m_finder`

- `Single m_initHeight`

- `Adapter m_adapter`

- `Single m_contentHeight`

- `Boolean m_canSwitch`

- `Boolean m_lock`

- `Coroutine m_lockCoroutine`

- `Boolean m_expanded`

- `Single m_switchPosition`

- `Tween m_switchTween`


## Methods

- `Void Render(StageStorylineSSViewModel)`

- `Void OnSwitchEvent()`

- `Void _InitIfNot()`

- `Void _ResetSwitch()`

- `Single _GetPosition()`

- `Void _SetPosition(Single)`

- `IEnumerator _LockSwitchForContentHeightCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryRetroSSTagView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _tagContent; // 0x18
	private LayoutGroup _tagLayout; // 0x20
	private RectTransform _tagViewport; // 0x28
	private CanvasGroup _defaultLayer; // 0x30
	private CanvasGroup _expandedLayer; // 0x38
	private List`1 _canSwitchPanels; // 0x40
	private Single _switchDuration; // 0x48
	private Ease _switchEase; // 0x4c
	private Boolean m_hasInited; // 0x50
	private UIPageFinder m_finder; // 0x58
	private Single m_initHeight; // 0x68
	private Adapter m_adapter; // 0x70
	private Single m_contentHeight; // 0x78
	private Boolean m_canSwitch; // 0x7c
	private Boolean m_lock; // 0x7d
	private Coroutine m_lockCoroutine; // 0x80
	private Boolean m_expanded; // 0x88
	private Single m_switchPosition; // 0x8c
	private Tween m_switchTween; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnSwitchEvent; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__ResetSwitch; // 0x18
	private static DelegateBridge __Hotfix0__GetPosition; // 0x20
	private static DelegateBridge __Hotfix0__SetPosition; // 0x28
	private static DelegateBridge __Hotfix0__LockSwitchForContentHeightCoroutine; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x300048c VA: 0x759561848c
	public Void Render(StageStorylineSSViewModel model) { }
	// RVA: 0x3000890 VA: 0x7595618890
	public Void OnSwitchEvent() { }
	// RVA: 0x30005e0 VA: 0x75956185e0
	private Void _InitIfNot() { }
	// RVA: 0x3000760 VA: 0x7595618760
	private Void _ResetSwitch() { }
	// RVA: 0x3000be4 VA: 0x7595618be4
	private Single _GetPosition() { }
	// RVA: 0x3000b04 VA: 0x7595618b04
	private Void _SetPosition(Single position) { }
	// RVA: 0x30007e4 VA: 0x75956187e4
	private IEnumerator _LockSwitchForContentHeightCoroutine() { }
	// RVA: 0x3000c74 VA: 0x7595618c74
	public Void .ctor() { }
}
```