# CharacterShowTalentItem

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `Text _textName`

- `Text _textDesc`

- `GameObject _unlockHintGo`

- `Text _textUnlockHint`

- `LayoutElement _layoutElement`

- `Single _baseHeight`

- `UIAtlasImage _imgUnlockIcon`

- `UIAtlasObject _atlasUnlockIcon`

- `String _iconLevelUpUnlockName`

- `String _iconEvolveOneUnlockName`

- `String _iconEvolveTwoUnlockName`

- `TextGenerator m_textGenerator`

- `String m_cachedDesc`


## Methods

- `Void Render(CharacterShowTalentModel, Boolean)`

- `String _GetUnlockIconName(CharacterShowTalentModel)`

- `String _GetUnlockHint(CharacterShowTalentModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowTalentItem : MonoBehaviour, IHotfixable
{
	private Text _textName; // 0x18
	private Text _textDesc; // 0x20
	private GameObject _unlockHintGo; // 0x28
	private Text _textUnlockHint; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private Single _baseHeight; // 0x40
	private UIAtlasImage _imgUnlockIcon; // 0x48
	private UIAtlasObject _atlasUnlockIcon; // 0x50
	private String _iconLevelUpUnlockName; // 0x58
	private String _iconEvolveOneUnlockName; // 0x60
	private String _iconEvolveTwoUnlockName; // 0x68
	private TextGenerator m_textGenerator; // 0x70
	private String m_cachedDesc; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetUnlockIconName; // 0x8
	private static DelegateBridge __Hotfix0__GetUnlockHint; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ce632c VA: 0x75952fe32c
	public Void Render(CharacterShowTalentModel talentModel, Boolean isUnlockHintVisible) { }
	// RVA: 0x2ce80a8 VA: 0x75953000a8
	private String _GetUnlockIconName(CharacterShowTalentModel talentModel) { }
	// RVA: 0x2ce7ed8 VA: 0x75952ffed8
	private String _GetUnlockHint(CharacterShowTalentModel talentModel) { }
	// RVA: 0x2ce8164 VA: 0x7595300164
	public Void .ctor() { }
}
```