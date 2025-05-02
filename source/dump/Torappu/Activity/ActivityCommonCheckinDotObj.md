# ActivityCommonCheckinDotObj

**Namespace:** `Torappu.Activity`


## Fields

- `Image _image`

- `Button _button`

- `Int32 m_index`


## Methods

- `Void SetClickListener(Int32, Action`1)`

- `Void SetImageAndColor(Sprite, Color)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonCheckinDotObj : MonoBehaviour, IHotfixable
{
	private Image _image; // 0x18
	private Button _button; // 0x20
	private Int32 m_index; // 0x28
	private Action`1 m_onClick; // 0x30
	private static DelegateBridge __Hotfix0_SetClickListener; // 0x0
	private static DelegateBridge __Hotfix0_SetImageAndColor; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30ccf54 VA: 0x75956e4f54
	public Void SetClickListener(Int32 index, Action`1 onClick) { }
	// RVA: 0x30cd090 VA: 0x75956e5090
	public Void SetImageAndColor(Sprite sprite, Color color) { }
	// RVA: 0x30cd194 VA: 0x75956e5194
	public Void EventOnClick() { }
	// RVA: 0x30cd21c VA: 0x75956e521c
	public Void .ctor() { }
}
```