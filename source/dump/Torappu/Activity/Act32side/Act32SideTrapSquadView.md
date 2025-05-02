# Act32SideTrapSquadView

**Namespace:** `Torappu.Activity.Act32side`


## Fields

- `GameObject _showObj`

- `UIAtlasObject _atlasObj`

- `GameObject _newFlag`

- `Boolean m_flagInfo`

- `String m_stageId`

- `String m_domainId`


## Methods

- `Void OpenTrapPage()`

- `Boolean <>xLuaBaseProxy_ShowSquadLeftArrow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act32side
public class Act32SideTrapSquadView : TemplateTrapSquadPlugin
{
	private const String UI_ICON_IMG; // 0x0
	private GameObject _showObj; // 0x30
	private List`1 _atlasImage; // 0x38
	private UIAtlasObject _atlasObj; // 0x40
	private GameObject _newFlag; // 0x48
	private Boolean m_flagInfo; // 0x50
	private String m_stageId; // 0x58
	private String m_domainId; // 0x60
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_ShowSquadLeftArrow; // 0x8
	private static DelegateBridge __Hotfix0_OpenTrapPage; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32577d0 VA: 0x759586f7d0
	public override Void Show(PluginInputParams param) { }
	// RVA: 0x3257be8 VA: 0x759586fbe8
	public override Boolean ShowSquadLeftArrow() { }
	// RVA: 0x3257c58 VA: 0x759586fc58
	public Void OpenTrapPage() { }
	// RVA: 0x3257d50 VA: 0x759586fd50
	public Void .ctor() { }
	// RVA: 0x3257dc0 VA: 0x759586fdc0
	private Boolean <>xLuaBaseProxy_ShowSquadLeftArrow() { }
}
```