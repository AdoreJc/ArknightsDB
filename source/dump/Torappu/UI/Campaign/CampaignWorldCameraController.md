# CampaignWorldCameraController

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `RectTransform _targetCanvas`

- `MobileTouchCamera _touchCamera`

- `Single _focusSpeed`

- `Single _focusMinDuration`

- `Boolean m_inited`

- `Int32 m_lock`

- `Tween m_tweener`


## Methods

- `Camera GetCamera()`

- `Vector3 GetIntersectPointOnCanvas()`

- `Void SetLock(LockSource, Boolean)`

- `Void Focus(FocusParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldCameraController : MonoBehaviour, IHotfixable
{
	private RectTransform _targetCanvas; // 0x18
	private MobileTouchCamera _touchCamera; // 0x20
	private Single _focusSpeed; // 0x28
	private Single _focusMinDuration; // 0x2c
	private Boolean m_inited; // 0x30
	private Int32 m_lock; // 0x34
	private Tween m_tweener; // 0x38
	private static DelegateBridge __Hotfix0_GetCamera; // 0x0
	private static DelegateBridge __Hotfix0_GetIntersectPointOnCanvas; // 0x8
	private static DelegateBridge __Hotfix0_SetLock; // 0x10
	private static DelegateBridge __Hotfix0_Focus; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2dd1330 VA: 0x75953e9330
	public Camera GetCamera() { }
	// RVA: 0x2dd13b8 VA: 0x75953e93b8
	public Vector3 GetIntersectPointOnCanvas() { }
	// RVA: 0x2dd1668 VA: 0x75953e9668
	public Void SetLock(LockSource lockSource, Boolean isLock) { }
	// RVA: 0x2dd1728 VA: 0x75953e9728
	public Void Focus(FocusParam param) { }
	// RVA: 0x2dd1c7c VA: 0x75953e9c7c
	public Void .ctor() { }
}
```