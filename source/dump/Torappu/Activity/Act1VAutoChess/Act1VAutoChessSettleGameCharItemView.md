# Act1VAutoChessSettleGameCharItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _tierIconImage`

- `Image _evolvePhaseIconImage`

- `Text _levelText`

- `Color _levelNormalColor`

- `Color _levelGoldenColor`

- `UIAtlasImage _portraitImage`

- `GameObject _isAssistPanel`

- `GameObject _isBackUpPanel`

- `GameObject _noSkillPanel`

- `GameObject _hasSkillPanel`

- `Image _skillIconImage`

- `GameObject _noEquipPanel`

- `GameObject _hasEquipPanel`

- `Image _equipIconImage`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`


## Methods

- `Void Render(CharViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessSettleGameCharItemView : MonoBehaviour, IHotfixable
{
	private Image _tierIconImage; // 0x18
	private Image _evolvePhaseIconImage; // 0x20
	private Text _levelText; // 0x28
	private Color _levelNormalColor; // 0x30
	private Color _levelGoldenColor; // 0x40
	private UIAtlasImage _portraitImage; // 0x50
	private GameObject _isAssistPanel; // 0x58
	private GameObject _isBackUpPanel; // 0x60
	private GameObject _noSkillPanel; // 0x68
	private GameObject _hasSkillPanel; // 0x70
	private Image _skillIconImage; // 0x78
	private GameObject _noEquipPanel; // 0x80
	private GameObject _hasEquipPanel; // 0x88
	private Image _equipIconImage; // 0x90
	private Boolean m_hasInited; // 0x98
	private ILoadAsset m_iLoadAsset; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3345b2c VA: 0x759595db2c
	public Void Render(CharViewModel model) { }
	// RVA: 0x3345fc0 VA: 0x759595dfc0
	private Void _InitIfNot() { }
	// RVA: 0x334606c VA: 0x759595e06c
	public Void .ctor() { }
}
```