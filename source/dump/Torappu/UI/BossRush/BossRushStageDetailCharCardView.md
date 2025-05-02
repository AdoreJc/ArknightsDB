# BossRushStageDetailCharCardView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `SimpleLayoutContent _characterPortraitContent`

- `TwoStateToggle _charEmptyToggle`

- `UIAtlasImage _charPortrait`

- `Image _charProfession`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `CharacterData m_cachedData`


## Methods

- `Void Render(String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailCharCardView : MonoBehaviour, IHotfixable
{
	private GameObject[] _characterPortraitBg; // 0x18
	private SimpleLayoutContent _characterPortraitContent; // 0x20
	private TwoStateToggle _charEmptyToggle; // 0x28
	private UIAtlasImage _charPortrait; // 0x30
	private Image _charProfession; // 0x38
	private Boolean m_hasInited; // 0x40
	private Adapter m_adapter; // 0x48
	private CharacterData m_cachedData; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2e71e40 VA: 0x7595489e40
	public Void Render(String charId) { }
	// RVA: 0x2e72110 VA: 0x759548a110
	private Void _InitIfNot() { }
	// RVA: 0x2e72274 VA: 0x759548a274
	public Void .ctor() { }
}
```