# CharacterInfoTalentGroup

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `SimpleLayoutContent _content`

- `GameObject _panelContent`

- `GameObject _panelEmpty`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void RenderDesc(CharacterTalentViewModel[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoTalentGroup : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private GameObject _panelContent; // 0x20
	private GameObject _panelEmpty; // 0x28
	private Adapter m_adapter; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d8cfd0 VA: 0x75953a4fd0
	private Void _InitIfNot() { }
	// RVA: 0x2d82e5c VA: 0x759539ae5c
	public Void RenderDesc(CharacterTalentViewModel[] talents) { }
	// RVA: 0x2d8d10c VA: 0x75953a510c
	public Void .ctor() { }
}
```