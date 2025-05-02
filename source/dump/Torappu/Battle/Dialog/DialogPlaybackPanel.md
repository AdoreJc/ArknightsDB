# DialogPlaybackPanel

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `DialogPlaybackTextView _avgPlaybackTextView`

- `ScrollRect _scrollView`

- `UIRecycleLayoutGroup _content`

- `ContentSizeFitterHelper _fitterHelper`

- `GameObject _closeBtn`

- `CanvasGroup m_canvasGroup`

- `UISwitchTween m_playbackTween`

- `Adapter m_innerAdapter`

- `Boolean m_isProcessingMultiline`

- `StringBuilder m_cachedStrBuilder`

- `Options m_multilineOption`

- `VirtualView m_multilineView`


## Properties

- `Adapter adapter`

- `CanvasGroup canvasGroup`

- `UISwitchTween fadeSwitchTween`

- `Boolean isShown`


## Methods

- `Adapter get_adapter()`

- `Void OnPointerClick(PointerEventData)`

- `Void OnReset()`

- `CanvasGroup get_canvasGroup()`

- `UISwitchTween get_fadeSwitchTween()`

- `Void _UpdateShown(Boolean, Boolean)`

- `Void _ResetLastCurrentIcon()`

- `Void _ResetScrollSlide()`

- `Boolean get_isShown()`

- `Void set_isShown(Boolean)`

- `Void OnCloseBtnClicked()`

- `Void AddDialog(String, String)`

- `Void AddOptions(List`1, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogPlaybackPanel : DialogExecutorBase, IPointerClickHandler, IEventSystemHandler
{
	private DialogPlaybackTextView _avgPlaybackTextView; // 0x18
	private ScrollRect _scrollView; // 0x20
	private UIRecycleLayoutGroup _content; // 0x28
	private ContentSizeFitterHelper _fitterHelper; // 0x30
	private GameObject _closeBtn; // 0x38
	private CanvasGroup m_canvasGroup; // 0x40
	private UISwitchTween m_playbackTween; // 0x48
	private Adapter m_innerAdapter; // 0x50
	private Boolean m_isProcessingMultiline; // 0x58
	private StringBuilder m_cachedStrBuilder; // 0x60
	private Options m_multilineOption; // 0x68
	private VirtualView m_multilineView; // 0x98
	private static DelegateBridge __Hotfix0_get_adapter; // 0x0
	private static DelegateBridge __Hotfix0_OnPointerClick; // 0x8
	private static DelegateBridge __Hotfix0_OnReset; // 0x10
	private static DelegateBridge __Hotfix0_get_canvasGroup; // 0x18
	private static DelegateBridge __Hotfix0_get_fadeSwitchTween; // 0x20
	private static DelegateBridge __Hotfix0__UpdateShown; // 0x28
	private static DelegateBridge __Hotfix0__ResetLastCurrentIcon; // 0x30
	private static DelegateBridge __Hotfix0__ResetScrollSlide; // 0x38
	private static DelegateBridge __Hotfix0_get_isShown; // 0x40
	private static DelegateBridge __Hotfix0_set_isShown; // 0x48
	private static DelegateBridge __Hotfix0_OnCloseBtnClicked; // 0x50
	private static DelegateBridge __Hotfix0_AddDialog; // 0x58
	private static DelegateBridge __Hotfix0_AddOptions; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	protected Adapter adapter { get; }
	private CanvasGroup canvasGroup { get; }
	private UISwitchTween fadeSwitchTween { get; }
	public Boolean isShown { get; set; }

	// RVA: 0x1d2673c VA: 0x759433e73c
	protected Adapter get_adapter() { }
	// RVA: 0x1d26938 VA: 0x759433e938
	public Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x1d21900 VA: 0x7594339900
	public Void OnReset() { }
	// RVA: 0x1d26a80 VA: 0x759433ea80
	private CanvasGroup get_canvasGroup() { }
	// RVA: 0x1d26b58 VA: 0x759433eb58
	private UISwitchTween get_fadeSwitchTween() { }
	// RVA: 0x1d269b0 VA: 0x759433e9b0
	private Void _UpdateShown(Boolean value, Boolean force) { }
	// RVA: 0x1d26c2c VA: 0x759433ec2c
	private Void _ResetLastCurrentIcon() { }
	// RVA: 0x1d26e84 VA: 0x759433ee84
	private Void _ResetScrollSlide() { }
	// RVA: 0x1d242bc VA: 0x759433c2bc
	public Boolean get_isShown() { }
	// RVA: 0x1d24334 VA: 0x759433c334
	public Void set_isShown(Boolean value) { }
	// RVA: 0x1d26efc VA: 0x759433eefc
	public Void OnCloseBtnClicked() { }
	// RVA: 0x1d233f0 VA: 0x759433b3f0
	public Void AddDialog(String text, String name) { }
	// RVA: 0x1d25904 VA: 0x759433d904
	public Void AddOptions(List`1 dialogueOptions, Int32 decision) { }
	// RVA: 0x1d270e4 VA: 0x759433f0e4
	public Void .ctor() { }
}
```