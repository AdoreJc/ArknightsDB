# UISpeedSwitcher

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Button _button`

- `Image _image`


## Methods

- `Void SyncToCurrentValue()`

- `Void SetInteractable(Boolean, Boolean)`

- `Void _OnSpeedLevelChanged(Object)`

- `Void _UpdateSpeedLevel()`

- `Void Start()`

- `Void OnDestroy()`

- `Boolean _IsFunctionDisabled()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UISpeedSwitcher : MonoBehaviour
{
	private Button _button; // 0x18
	private Sprite[] _sprites; // 0x20
	private Image _image; // 0x28

	public virtual Boolean interactable { get; }

	// RVA: 0x2082d50 VA: 0x759469ad50
	public virtual Boolean get_interactable() { }
	// RVA: 0x2082de8 VA: 0x759469ade8
	public Void SyncToCurrentValue() { }
	// RVA: 0x2082eb8 VA: 0x759469aeb8
	public Void SetInteractable(Boolean val, Boolean force) { }
	// RVA: 0x2082f04 VA: 0x759469af04
	private Void _OnSpeedLevelChanged(Object arg) { }
	// RVA: 0x2082dec VA: 0x759469adec
	private Void _UpdateSpeedLevel() { }
	// RVA: 0x2082f08 VA: 0x759469af08
	private Void Start() { }
	// RVA: 0x2082fe0 VA: 0x759469afe0
	private Void OnDestroy() { }
	// RVA: 0x2082d88 VA: 0x759469ad88
	private Boolean _IsFunctionDisabled() { }
	// RVA: 0x2083104 VA: 0x759469b104
	public Void .ctor() { }
}
```