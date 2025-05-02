# UIItemTimeCountDown

**Namespace:** `Torappu.UI`


## Fields

- `TimeStyleConfig _timeStyleEmer`

- `TimeStyleConfig _timeStyleWarn`

- `TimeStyleConfig _timeStyleSafe`

- `Image _imgTimeBkg`

- `Image _imgTimeIcon`

- `Text _textTime`

- `GameObject _panelTime`

- `CountDownTask m_validTimeTask`

- `ItemValidTimeLevel m_validTimeLevel`


## Methods

- `Void SetScaler(Single)`

- `Void _OnValidTimeTick(TickValue)`

- `Void ApplyCountDown(Action, Int64)`

- `Void CleanCountDown()`

- `Void RegisterCountDown()`

- `Void UnRegisterCountDown()`

- `Void _UpdateValidTimeStyle(ItemValidTimeLevel)`

- `Boolean _IsOverrideTimeStyleEmpty()`

- `Void OnDestroy()`

- `Void UpdateTime(Single)`

- `Void OverrideStyleConfig(Color, Color, Color)`

- `Void ClearOverrideStyle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemTimeCountDown : MonoBehaviour, ITimeWatcher, IHotfixable
{
	private TimeStyleConfig _timeStyleEmer; // 0x18
	private TimeStyleConfig _timeStyleWarn; // 0x48
	private TimeStyleConfig _timeStyleSafe; // 0x78
	private Image _imgTimeBkg; // 0xa8
	private Image _imgTimeIcon; // 0xb0
	private Text _textTime; // 0xb8
	private GameObject _panelTime; // 0xc0
	private CountDownTask m_validTimeTask; // 0xc8
	private ItemValidTimeLevel m_validTimeLevel; // 0xd0
	private Nullable`1 m_overrideTimeStyle; // 0xd4
	private static DelegateBridge __Hotfix0_SetScaler; // 0x0
	private static DelegateBridge __Hotfix0__OnValidTimeTick; // 0x8
	private static DelegateBridge __Hotfix0_ApplyCountDown; // 0x10
	private static DelegateBridge __Hotfix0_CleanCountDown; // 0x18
	private static DelegateBridge __Hotfix0_RegisterCountDown; // 0x20
	private static DelegateBridge __Hotfix0_UnRegisterCountDown; // 0x28
	private static DelegateBridge __Hotfix0__UpdateValidTimeStyle; // 0x30
	private static DelegateBridge __Hotfix0__IsOverrideTimeStyleEmpty; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x48
	private static DelegateBridge __Hotfix0_OverrideStyleConfig; // 0x50
	private static DelegateBridge __Hotfix0_ClearOverrideStyle; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x218b7dc VA: 0x75947a37dc
	public Void SetScaler(Single scale) { }
	// RVA: 0x2193444 VA: 0x75947ab444
	private Void _OnValidTimeTick(TickValue tick) { }
	// RVA: 0x218bcdc VA: 0x75947a3cdc
	public Void ApplyCountDown(Action onTimeOut, Int64 remainSecs) { }
	// RVA: 0x218be38 VA: 0x75947a3e38
	public Void CleanCountDown() { }
	// RVA: 0x218bbfc VA: 0x75947a3bfc
	public Void RegisterCountDown() { }
	// RVA: 0x218bc6c VA: 0x75947a3c6c
	public Void UnRegisterCountDown() { }
	// RVA: 0x2193528 VA: 0x75947ab528
	private Void _UpdateValidTimeStyle(ItemValidTimeLevel level) { }
	// RVA: 0x21937a8 VA: 0x75947ab7a8
	private Boolean _IsOverrideTimeStyleEmpty() { }
	// RVA: 0x2193824 VA: 0x75947ab824
	private Void OnDestroy() { }
	// RVA: 0x2193894 VA: 0x75947ab894
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x2193928 VA: 0x75947ab928
	public Void OverrideStyleConfig(Color bkgColor, Color iconColor, Color textColor) { }
	// RVA: 0x2193a74 VA: 0x75947aba74
	public Void ClearOverrideStyle() { }
	// RVA: 0x2193ae8 VA: 0x75947abae8
	public Void .ctor() { }
}
```