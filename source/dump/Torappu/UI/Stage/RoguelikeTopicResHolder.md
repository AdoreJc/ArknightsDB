# RoguelikeTopicResHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Sprite _entryImg`

- `Sprite _backImg`

- `Sprite _permModeEntryImg`

- `Color _themeColor`


## Properties

- `Sprite entryImg`

- `Sprite backImg`

- `Sprite permModeEntryImg`

- `Color themeColor`


## Methods

- `Sprite get_entryImg()`

- `Sprite get_backImg()`

- `Sprite get_permModeEntryImg()`

- `Color get_themeColor()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class RoguelikeTopicResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _entryImg; // 0x18
	private Sprite _backImg; // 0x20
	private Sprite _permModeEntryImg; // 0x28
	private Color _themeColor; // 0x30
	private static DelegateBridge __Hotfix0_get_entryImg; // 0x0
	private static DelegateBridge __Hotfix0_get_backImg; // 0x8
	private static DelegateBridge __Hotfix0_get_permModeEntryImg; // 0x10
	private static DelegateBridge __Hotfix0_get_themeColor; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Sprite entryImg { get; }
	public Sprite backImg { get; }
	public Sprite permModeEntryImg { get; }
	public Color themeColor { get; }

	// RVA: 0x2f130f8 VA: 0x759552b0f8
	public Sprite get_entryImg() { }
	// RVA: 0x2f131d0 VA: 0x759552b1d0
	public Sprite get_backImg() { }
	// RVA: 0x2f132a8 VA: 0x759552b2a8
	public Sprite get_permModeEntryImg() { }
	// RVA: 0x2f13380 VA: 0x759552b380
	public Color get_themeColor() { }
	// RVA: 0x2f133e8 VA: 0x759552b3e8
	public Void .ctor() { }
}
```