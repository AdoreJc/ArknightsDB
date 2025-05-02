# ArchiveChallengeBookListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Text _storyNameText`

- `Text _storyContentText`

- `ScrollRect _storyContentScrollRect`

- `SimpleLayoutContent _itemContent`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Boolean m_cachedShowTween`

- `ChallengeBookItemModel m_cachedSelectedItem`

- `ArchiveChallengeBookController <controller>k__BackingField`


## Properties

- `ArchiveChallengeBookController controller`


## Methods

- `ArchiveChallengeBookController get_controller()`

- `Void set_controller(ArchiveChallengeBookController)`

- `Void _InitIfNot()`

- `String _LoadTextContent(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChallengeBookListDataBinder : DataBinder`1
{
	private Text _storyNameText; // 0x20
	private Text _storyContentText; // 0x28
	private ScrollRect _storyContentScrollRect; // 0x30
	private SimpleLayoutContent _itemContent; // 0x38
	private Boolean m_hasInited; // 0x40
	private Adapter m_adapter; // 0x48
	private List`1 m_cachedItems; // 0x50
	private Boolean m_cachedShowTween; // 0x58
	private ChallengeBookItemModel m_cachedSelectedItem; // 0x60
	private ArchiveChallengeBookController <controller>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__LoadTextContent; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ArchiveChallengeBookController controller { get; set; }

	// RVA: 0x303d5b4 VA: 0x75956555b4
	private ArchiveChallengeBookController get_controller() { }
	// RVA: 0x303d61c VA: 0x759565561c
	public Void set_controller(ArchiveChallengeBookController value) { }
	// RVA: 0x303d6a0 VA: 0x75956556a0
	public override Void OnValueChanged(ChallengeBookProperty property) { }
	// RVA: 0x303d824 VA: 0x7595655824
	private Void _InitIfNot() { }
	// RVA: 0x303da2c VA: 0x7595655a2c
	private String _LoadTextContent(String textId) { }
	// RVA: 0x303dbc8 VA: 0x7595655bc8
	public Void .ctor() { }
}
```