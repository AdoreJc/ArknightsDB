# LocationHandler

**Namespace:** ` `


## Fields

- `Rl03OuterBuffView m_closure`

- `Int32 m_leftIndex`

- `Int32 m_rightIndex`

- `Tween m_focusTween`

- `FadeSwitchTween m_leftSwitchTween`

- `FadeSwitchTween m_rightSwitchTween`


## Methods

- `Void UpdateLocation()`

- `Void FocusLeft()`

- `Void FocusRight()`

- `Void FocusIndex(Int32, Boolean)`

- `Void _UpdateLocationButtonsStatus()`

- `Void _UpdateLocation()`

- `Void _FocusLocationImmediately(Int32)`

- `Void _FocusLocation(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LocationHandler : IHotfixable
{
	private Rl03OuterBuffView m_closure; // 0x10
	private Int32 m_leftIndex; // 0x18
	private Int32 m_rightIndex; // 0x1c
	private Tween m_focusTween; // 0x20
	private FadeSwitchTween m_leftSwitchTween; // 0x28
	private FadeSwitchTween m_rightSwitchTween; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateLocation; // 0x8
	private static DelegateBridge __Hotfix0_FocusLeft; // 0x10
	private static DelegateBridge __Hotfix0_FocusRight; // 0x18
	private static DelegateBridge __Hotfix0_FocusIndex; // 0x20
	private static DelegateBridge __Hotfix0__UpdateLocationButtonsStatus; // 0x28
	private static DelegateBridge __Hotfix0__UpdateLocation; // 0x30
	private static DelegateBridge __Hotfix0__FocusLocationImmediately; // 0x38
	private static DelegateBridge __Hotfix0__FocusLocation; // 0x40


	// RVA: 0x26b0b20 VA: 0x7594cc8b20
	public Void .ctor(Rl03OuterBuffView closure) { }
	// RVA: 0x26afde8 VA: 0x7594cc7de8
	public Void UpdateLocation() { }
	// RVA: 0x26b0ec4 VA: 0x7594cc8ec4
	public Void FocusLeft() { }
	// RVA: 0x26b0fb8 VA: 0x7594cc8fb8
	public Void FocusRight() { }
	// RVA: 0x26b0d48 VA: 0x7594cc8d48
	public Void FocusIndex(Int32 index, Boolean fastMode) { }
	// RVA: 0x26b1580 VA: 0x7594cc9580
	private Void _UpdateLocationButtonsStatus() { }
	// RVA: 0x26b1338 VA: 0x7594cc9338
	private Void _UpdateLocation() { }
	// RVA: 0x26b177c VA: 0x7594cc977c
	private Void _FocusLocationImmediately(Int32 index) { }
	// RVA: 0x26b165c VA: 0x7594cc965c
	private Void _FocusLocation(Int32 index) { }
}
```