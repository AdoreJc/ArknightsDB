# ActMultiV3EntryJoinRoomMask

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `CanvasGroup _canvasMask`

- `GameObject _raycastBlocker`

- `Single _waitTime`

- `Boolean m_inited`

- `UIPageFinder m_pageFinder`

- `Coroutine m_showCoroutine`

- `FadeSwitchTween m_showTween`

- `Status m_status`

- `Action m_cachedCallback`

- `Double <longTimeThreshold>k__BackingField`


## Properties

- `Double longTimeThreshold`

- `Boolean isStable`


## Methods

- `Double get_longTimeThreshold()`

- `Void set_longTimeThreshold(Double)`

- `Boolean get_isStable()`

- `Void _InitIfNot()`

- `Void _TriggerCallback()`

- `IEnumerator _ShowMaskCoroutine()`

- `Void ShowMask(Action)`

- `Void HideMask(Action)`

- `Void ResetMask()`

- `Void OnDestroy()`

- `Boolean <_ShowMaskCoroutine>b__18_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntryJoinRoomMask : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasMask; // 0x18
	private GameObject _raycastBlocker; // 0x20
	private Single _waitTime; // 0x28
	private Boolean m_inited; // 0x2c
	private UIPageFinder m_pageFinder; // 0x30
	private Coroutine m_showCoroutine; // 0x40
	private FadeSwitchTween m_showTween; // 0x48
	private Status m_status; // 0x50
	private Action m_cachedCallback; // 0x58
	private Double <longTimeThreshold>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_longTimeThreshold; // 0x0
	private static DelegateBridge __Hotfix0_set_longTimeThreshold; // 0x8
	private static DelegateBridge __Hotfix0_get_isStable; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__TriggerCallback; // 0x20
	private static DelegateBridge __Hotfix0__ShowMaskCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_ShowMask; // 0x30
	private static DelegateBridge __Hotfix0_HideMask; // 0x38
	private static DelegateBridge __Hotfix0_ResetMask; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Double longTimeThreshold { get; set; }
	public Boolean isStable { get; }

	// RVA: 0x30e701c VA: 0x75956ff01c
	private Double get_longTimeThreshold() { }
	// RVA: 0x30e7084 VA: 0x75956ff084
	public Void set_longTimeThreshold(Double value) { }
	// RVA: 0x30e7100 VA: 0x75956ff100
	public Boolean get_isStable() { }
	// RVA: 0x30e7170 VA: 0x75956ff170
	private Void _InitIfNot() { }
	// RVA: 0x30e7240 VA: 0x75956ff240
	private Void _TriggerCallback() { }
	// RVA: 0x30e7354 VA: 0x75956ff354
	private IEnumerator _ShowMaskCoroutine() { }
	// RVA: 0x30e7428 VA: 0x75956ff428
	public Void ShowMask(Action callback) { }
	// RVA: 0x30e750c VA: 0x75956ff50c
	public Void HideMask(Action callback) { }
	// RVA: 0x30e75c0 VA: 0x75956ff5c0
	public Void ResetMask() { }
	// RVA: 0x30e76b0 VA: 0x75956ff6b0
	private Void OnDestroy() { }
	// RVA: 0x30e7718 VA: 0x75956ff718
	public Void .ctor() { }
	// RVA: 0x30e7788 VA: 0x75956ff788
	private Boolean <_ShowMaskCoroutine>b__18_0() { }
}
```