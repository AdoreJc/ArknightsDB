# AutoFocusScrollView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ScrollRect _scrollView`

- `RectTransform _scrollViewRect`

- `Single _itemSize`

- `Single _itemSpacing`

- `Single _marginFront`

- `Single _marginEnd`

- `Boolean _horizontal`

- `Boolean m_layoutConstructCompleted`

- `FocusParams m_pendingParam`

- `Tween m_tween`


## Methods

- `Void StartSpawnChildren()`

- `Void FocusOnIndex(Int32, Int32, Boolean, Single)`

- `Void _ProcessParam(FocusParams)`

- `Void <StartSpawnChildren>b__11_0()`

- `Void <_ProcessParam>b__13_0()`

- `Void <_ProcessParam>b__13_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class AutoFocusScrollView : MonoBehaviour, IHotfixable
{
	private ScrollRect _scrollView; // 0x18
	private RectTransform _scrollViewRect; // 0x20
	private Single _itemSize; // 0x28
	private Single _itemSpacing; // 0x2c
	private Single _marginFront; // 0x30
	private Single _marginEnd; // 0x34
	private Boolean _horizontal; // 0x38
	private Boolean m_layoutConstructCompleted; // 0x39
	private FocusParams m_pendingParam; // 0x40
	private Tween m_tween; // 0x48
	private static DelegateBridge __Hotfix0_StartSpawnChildren; // 0x0
	private static DelegateBridge __Hotfix0_FocusOnIndex; // 0x8
	private static DelegateBridge __Hotfix0__ProcessParam; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30141a0 VA: 0x759562c1a0
	public Void StartSpawnChildren() { }
	// RVA: 0x30142fc VA: 0x759562c2fc
	public Void FocusOnIndex(Int32 index, Int32 count, Boolean fastMode, Single duration) { }
	// RVA: 0x3014420 VA: 0x759562c420
	private Void _ProcessParam(FocusParams param) { }
	// RVA: 0x3014698 VA: 0x759562c698
	public Void .ctor() { }
	// RVA: 0x3014708 VA: 0x759562c708
	private Void <StartSpawnChildren>b__11_0() { }
	// RVA: 0x3014740 VA: 0x759562c740
	private Void <_ProcessParam>b__13_0() { }
	// RVA: 0x301476c VA: 0x759562c76c
	private Void <_ProcessParam>b__13_1() { }
}
```