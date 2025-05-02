# HomeActTabOnBattle

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _iconActivity`

- `LayoutElement _layoutSize`

- `Button _button`

- `GameObject _panelLocked`

- `Options m_options`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(Options)`

- `Void _UpdateEntryInfo()`

- `Void _UpdateUnlockStatus()`

- `Void EventOnActivtyClicked()`

- `Void EventOnLockViewClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeActTabOnBattle : MonoBehaviour, IHotfixable
{
	private Image _iconActivity; // 0x18
	private LayoutElement _layoutSize; // 0x20
	private Button _button; // 0x28
	private GameObject _panelLocked; // 0x30
	public Action`1 onClicked; // 0x38
	private Options m_options; // 0x40
	private UIStateFinder m_stateFinder; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateEntryInfo; // 0x8
	private static DelegateBridge __Hotfix0__UpdateUnlockStatus; // 0x10
	private static DelegateBridge __Hotfix0__LoadEntryIcon; // 0x18
	private static DelegateBridge __Hotfix0__LoadActivityIcon; // 0x20
	private static DelegateBridge __Hotfix0__LoadCrisisV2Icon; // 0x28
	private static DelegateBridge __Hotfix0__LoadRoguelikeIcon; // 0x30
	private static DelegateBridge __Hotfix0__LoadMainlineIcon; // 0x38
	private static DelegateBridge __Hotfix0__LoadSandboxPermIcon; // 0x40
	private static DelegateBridge __Hotfix0_EventOnActivtyClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnLockViewClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2832ed4 VA: 0x7594e4aed4
	public Void Render(Options options) { }
	// RVA: 0x2833238 VA: 0x7594e4b238
	private Void _UpdateEntryInfo() { }
	// RVA: 0x28333d8 VA: 0x7594e4b3d8
	private Void _UpdateUnlockStatus() { }
	// RVA: 0x2833468 VA: 0x7594e4b468
	private static Sprite _LoadEntryIcon(Options options, ILoadAsset loader) { }
	// RVA: 0x28337f4 VA: 0x7594e4b7f4
	private static Sprite _LoadActivityIcon(Options options, ILoadAsset loader) { }
	// RVA: 0x2833a20 VA: 0x7594e4ba20
	private static Sprite _LoadCrisisV2Icon(Options options, ILoadAsset loader) { }
	// RVA: 0x2833c24 VA: 0x7594e4bc24
	private static Sprite _LoadRoguelikeIcon(Options options, ILoadAsset loader) { }
	// RVA: 0x2833e2c VA: 0x7594e4be2c
	private static Sprite _LoadMainlineIcon(Options options, ILoadAsset loader) { }
	// RVA: 0x2834030 VA: 0x7594e4c030
	private static Sprite _LoadSandboxPermIcon(Options options, ILoadAsset loader) { }
	// RVA: 0x2834238 VA: 0x7594e4c238
	public Void EventOnActivtyClicked() { }
	// RVA: 0x28342c0 VA: 0x7594e4c2c0
	public Void EventOnLockViewClicked() { }
	// RVA: 0x2834380 VA: 0x7594e4c380
	public Void .ctor() { }
}
```