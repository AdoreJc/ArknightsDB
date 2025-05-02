# ArchiveChaosListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _iconImage`

- `ArchiveChaosSideView _leftSideView`

- `ArchiveChaosSideView _rightSideView`

- `SimpleLayoutContent _content`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `String m_cachedSelectedItemId`

- `Boolean m_showSwitchAnim`

- `ArchiveChaosController <controller>k__BackingField`


## Properties

- `ArchiveChaosController controller`


## Methods

- `ArchiveChaosController get_controller()`

- `Void set_controller(ArchiveChaosController)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChaosListDataBinder : DataBinder`1
{
	private static readonly Color ATTAINED_COLOR; // 0x0
	private static readonly Color UNATTAINED_COLOR; // 0x10
	private Image _iconImage; // 0x20
	private ArchiveChaosSideView _leftSideView; // 0x28
	private ArchiveChaosSideView _rightSideView; // 0x30
	private SimpleLayoutContent _content; // 0x38
	private Boolean m_hasInited; // 0x40
	private Adapter m_adapter; // 0x48
	private List`1 m_cachedItems; // 0x50
	private String m_cachedSelectedItemId; // 0x58
	private Boolean m_showSwitchAnim; // 0x60
	private ArchiveChaosController <controller>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_controller; // 0x20
	private static DelegateBridge __Hotfix0_set_controller; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private ArchiveChaosController controller { get; set; }

	// RVA: 0x3040310 VA: 0x7595658310
	private ArchiveChaosController get_controller() { }
	// RVA: 0x3040388 VA: 0x7595658388
	public Void set_controller(ArchiveChaosController value) { }
	// RVA: 0x304041c VA: 0x759565841c
	public override Void OnValueChanged(ChaosProperty property) { }
	// RVA: 0x3040640 VA: 0x7595658640
	private Void _InitIfNot() { }
	// RVA: 0x3040c08 VA: 0x7595658c08
	public Void .ctor() { }
	// RVA: 0x3040ca8 VA: 0x7595658ca8
	private static Void .cctor() { }
}
```