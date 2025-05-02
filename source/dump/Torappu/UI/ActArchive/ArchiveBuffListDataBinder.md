# ArchiveBuffListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _icon`

- `Image _iconBack`

- `Text _name`

- `Text _usage`

- `Text _desc`

- `SimpleLayoutContent _groupContent`

- `ActArchiveController m_controller`

- `Boolean m_isInited`

- `ArchiveBuffGroupAdapter m_adapter`

- `BuffProxy m_proxy`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveBuffListDataBinder : DataBinder`1
{
	private Image _icon; // 0x20
	private Image _iconBack; // 0x28
	private Text _name; // 0x30
	private Text _usage; // 0x38
	private Text _desc; // 0x40
	private SimpleLayoutContent _groupContent; // 0x48
	private ActArchiveController m_controller; // 0x50
	private Boolean m_isInited; // 0x58
	private ArchiveBuffGroupAdapter m_adapter; // 0x60
	protected BuffProxy m_proxy; // 0x68
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ActArchiveController controller { get; set; }

	// RVA: 0x3037d20 VA: 0x759564fd20
	private ActArchiveController get_controller() { }
	// RVA: 0x3037c1c VA: 0x759564fc1c
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x3037f74 VA: 0x759564ff74
	public override Void OnValueChanged(BuffProperty property) { }
	// RVA: 0x3037d88 VA: 0x759564fd88
	private Void _InitIfNot() { }
	// RVA: 0x303840c VA: 0x759565040c
	public Void .ctor() { }
}
```