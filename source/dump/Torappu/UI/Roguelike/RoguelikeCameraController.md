# RoguelikeCameraController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `MobileTouchCamera _touchCamera`

- `RectTransform _rootRect`

- `Single _boundMargin`

- `Single _focusBoundLeft`

- `Single _focusBoundRight`

- `Ease _focusEasyType`

- `Single _focusSpeed`

- `Single _focusMinDuration`

- `Tween m_tweener`

- `Int32 m_lock`


## Methods

- `Void _EventOnDungeonZoneInit(Object)`

- `Void _EventOnDungeonNodeClick(Object)`

- `Void Init(RoguelikeDungeonController)`

- `Void SetLock(LockSource, Boolean)`

- `Void SetCameraBounds(Bounds)`

- `Void Focus(Bounds, Boolean)`

- `Void _ResetZoom()`

- `Vector3 <Focus>b__16_0()`

- `Void <Focus>b__16_1(Vector3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCameraController : PageSingleComponent
{
	private MobileTouchCamera _touchCamera; // 0x20
	private RectTransform _rootRect; // 0x28
	private Single _boundMargin; // 0x30
	private Single _focusBoundLeft; // 0x34
	private Single _focusBoundRight; // 0x38
	private Ease _focusEasyType; // 0x3c
	private Single _focusSpeed; // 0x40
	private Single _focusMinDuration; // 0x44
	private Tween m_tweener; // 0x48
	private Int32 m_lock; // 0x50
	private static DelegateBridge __Hotfix0__EventOnDungeonZoneInit; // 0x0
	private static DelegateBridge __Hotfix0__EventOnDungeonNodeClick; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_SetLock; // 0x18
	private static DelegateBridge __Hotfix0_SetCameraBounds; // 0x20
	private static DelegateBridge __Hotfix0_Focus; // 0x28
	private static DelegateBridge __Hotfix0__ResetZoom; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2aa5e78 VA: 0x75950bde78
	private Void _EventOnDungeonZoneInit(Object arg) { }
	// RVA: 0x2aa64c0 VA: 0x75950be4c0
	private Void _EventOnDungeonNodeClick(Object arg) { }
	// RVA: 0x2aa65b4 VA: 0x75950be5b4
	public Void Init(RoguelikeDungeonController controller) { }
	// RVA: 0x2aa6914 VA: 0x75950be914
	public Void SetLock(LockSource lockSource, Boolean isLock) { }
	// RVA: 0x2aa5f88 VA: 0x75950bdf88
	public Void SetCameraBounds(Bounds worldBounds) { }
	// RVA: 0x2aa6084 VA: 0x75950be084
	public Void Focus(Bounds worldBounds, Boolean useTween) { }
	// RVA: 0x2aa6770 VA: 0x75950be770
	private Void _ResetZoom() { }
	// RVA: 0x2aa69d4 VA: 0x75950be9d4
	public Void .ctor() { }
	// RVA: 0x2aa6a6c VA: 0x75950bea6c
	private Vector3 <Focus>b__16_0() { }
	// RVA: 0x2aa6a94 VA: 0x75950bea94
	private Void <Focus>b__16_1(Vector3 val) { }
}
```