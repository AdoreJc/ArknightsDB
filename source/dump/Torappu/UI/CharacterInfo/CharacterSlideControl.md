# CharacterSlideControl

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `UIIntEvent _onMove`

- `UIIntEvent _onRelease`

- `UIIntEvent _onEndDrag`

- `Int32 m_Cache`

- `Boolean m_OnDrag`

- `Boolean m_OnTween`

- `DateTime m_time`


## Methods

- `Void OnMouseDown()`

- `Void OnMouseUp()`

- `IEnumerator TweenTo(Single)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterSlideControl : MonoBehaviour, IHotfixable
{
	private UIIntEvent _onMove; // 0x18
	private UIIntEvent _onRelease; // 0x20
	private UIIntEvent _onEndDrag; // 0x28
	private Int32 m_Cache; // 0x30
	private Boolean m_OnDrag; // 0x34
	private Boolean m_OnTween; // 0x35
	private DateTime m_time; // 0x38
	private const Int32 MOUSEDELTAMAX; // 0x0
	private const Single DELTATHEROTIME; // 0x0
	private static DelegateBridge __Hotfix0_OnMouseDown; // 0x0
	private static DelegateBridge __Hotfix0_OnMouseUp; // 0x8
	private static DelegateBridge __Hotfix0_TweenTo; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d695d8 VA: 0x75953815d8
	public Void OnMouseDown() { }
	// RVA: 0x2d696a0 VA: 0x75953816a0
	public Void OnMouseUp() { }
	// RVA: 0x2d6973c VA: 0x759538173c
	private IEnumerator TweenTo(Single currentPos) { }
	// RVA: 0x2d69828 VA: 0x7595381828
	private Void Update() { }
	// RVA: 0x2d69904 VA: 0x7595381904
	public Void .ctor() { }
}
```