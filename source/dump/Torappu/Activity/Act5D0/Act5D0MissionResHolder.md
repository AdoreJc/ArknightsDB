# Act5D0MissionResHolder

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Sprite _backImg`

- `Color _diffColor`

- `Color _diffAppendColor`

- `Color _titleColor`

- `Color _descColor`

- `Color _rewardCountColor`

- `Color _crossColor`


## Properties

- `Sprite backImg`

- `Color diffColor`

- `Color diffAppendColor`

- `Color titleColor`

- `Color descColor`

- `Color rewardCountColor`

- `Color crossColor`


## Methods

- `Sprite get_backImg()`

- `Color get_diffColor()`

- `Color get_diffAppendColor()`

- `Color get_titleColor()`

- `Color get_descColor()`

- `Color get_rewardCountColor()`

- `Color get_crossColor()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MissionResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _backImg; // 0x18
	private Color _diffColor; // 0x20
	private Color _diffAppendColor; // 0x30
	private Color _titleColor; // 0x40
	private Color _descColor; // 0x50
	private Color _rewardCountColor; // 0x60
	private Color _crossColor; // 0x70
	private static DelegateBridge __Hotfix0_get_backImg; // 0x0
	private static DelegateBridge __Hotfix0_get_diffColor; // 0x8
	private static DelegateBridge __Hotfix0_get_diffAppendColor; // 0x10
	private static DelegateBridge __Hotfix0_get_titleColor; // 0x18
	private static DelegateBridge __Hotfix0_get_descColor; // 0x20
	private static DelegateBridge __Hotfix0_get_rewardCountColor; // 0x28
	private static DelegateBridge __Hotfix0_get_crossColor; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Sprite backImg { get; }
	public Color diffColor { get; }
	public Color diffAppendColor { get; }
	public Color titleColor { get; }
	public Color descColor { get; }
	public Color rewardCountColor { get; }
	public Color crossColor { get; }

	// RVA: 0x31b8f98 VA: 0x75957d0f98
	public Sprite get_backImg() { }
	// RVA: 0x31b9000 VA: 0x75957d1000
	public Color get_diffColor() { }
	// RVA: 0x31b9068 VA: 0x75957d1068
	public Color get_diffAppendColor() { }
	// RVA: 0x31b90d0 VA: 0x75957d10d0
	public Color get_titleColor() { }
	// RVA: 0x31b9138 VA: 0x75957d1138
	public Color get_descColor() { }
	// RVA: 0x31b91a0 VA: 0x75957d11a0
	public Color get_rewardCountColor() { }
	// RVA: 0x31b9208 VA: 0x75957d1208
	public Color get_crossColor() { }
	// RVA: 0x31b9270 VA: 0x75957d1270
	public Void .ctor() { }
}
```