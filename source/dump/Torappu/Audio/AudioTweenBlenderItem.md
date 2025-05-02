# AudioTweenBlenderItem

**Namespace:** `Torappu.Audio`


## Fields

- `Single endValue`

- `Single duration`

- `Single delay`

- `Int32 sequenceNum`

- `Single startValue`

- `Single defaultValue`

- `EaseType easeType`

- `EaseType reverseEaseType`

- `Boolean ignoreTimeScale`

- `Boolean stopAfterTween`

- `SmoothStep m_valueTween`


## Methods

- `Void Start()`

- `Void Remove(Boolean)`

- `Single GetValue()`

- `Boolean IsItemActive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioTweenBlenderItem : IHotfixable
{
	public Single endValue; // 0x10
	public Single duration; // 0x14
	public Single delay; // 0x18
	public Int32 sequenceNum; // 0x1c
	public Single startValue; // 0x20
	public Single defaultValue; // 0x24
	public EaseType easeType; // 0x28
	public EaseType reverseEaseType; // 0x2c
	public Boolean ignoreTimeScale; // 0x30
	public Boolean stopAfterTween; // 0x31
	private SmoothStep m_valueTween; // 0x38
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_Remove; // 0x8
	private static DelegateBridge __Hotfix0_GetValue; // 0x10
	private static DelegateBridge __Hotfix0_IsItemActive; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3eb89f8 VA: 0x75964d09f8
	public Void Start() { }
	// RVA: 0x3eb8ad4 VA: 0x75964d0ad4
	public Void Remove(Boolean needReverseTween) { }
	// RVA: 0x3eb8c1c VA: 0x75964d0c1c
	public Single GetValue() { }
	// RVA: 0x3eb8ce0 VA: 0x75964d0ce0
	public Boolean IsItemActive() { }
	// RVA: 0x3eb8dc4 VA: 0x75964d0dc4
	public Void .ctor() { }
}
```