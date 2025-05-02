# BuildingSMRoomCharView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `BuildingCharAvatar _charAvatar`

- `GameObject _dormLockBg`

- `GameObject _dormLockFrame`

- `GameObject _dormLockFrameActive`

- `CanvasGroup _iconInPreQue`

- `Boolean m_isInited`

- `Boolean m_isEditMode`

- `Boolean m_isDormLockInEditMode`

- `FadeSwitchTween m_queIconFadeTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(StationRoomStructModel, StationCharStructModel, Int32, Boolean)`

- `Void _InitIfNot()`

- `Void _OnCharClicked(BuildingCharModel, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMRoomCharView : MonoBehaviour, IHotfixable
{
	private BuildingCharAvatar _charAvatar; // 0x18
	private GameObject _dormLockBg; // 0x20
	private GameObject _dormLockFrame; // 0x28
	private GameObject _dormLockFrameActive; // 0x30
	private CanvasGroup _iconInPreQue; // 0x38
	public Action`2 onCharClicked; // 0x40
	private Boolean m_isInited; // 0x48
	private Boolean m_isEditMode; // 0x49
	private Boolean m_isDormLockInEditMode; // 0x4a
	private FadeSwitchTween m_queIconFadeTween; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnCharClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3dac35c VA: 0x75963c435c
	public Void Render(StationRoomStructModel roomModel, StationCharStructModel charSlotModel, Int32 position, Boolean isEditDormLock) { }
	// RVA: 0x3dac6e4 VA: 0x75963c46e4
	private Void _InitIfNot() { }
	// RVA: 0x3dac7c8 VA: 0x75963c47c8
	private Void _OnCharClicked(BuildingCharModel target, Object param) { }
	// RVA: 0x3dac8f8 VA: 0x75963c48f8
	public Void .ctor() { }
}
```