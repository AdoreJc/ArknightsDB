# CharacterInfoRightProfTalentView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _talentName`

- `Text _textContent`

- `CharacterInfoTalentUnlockView _unlockView`

- `Single cacheHeight`

- `TextGenerator m_textGenerate`

- `CharacterTalentViewModel m_viewModel`


## Methods

- `Single CalcHeight()`

- `Void Render(CharacterTalentViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightProfTalentView : CharacterInfoRightProfObj
{
	private Text _talentName; // 0x20
	private Text _textContent; // 0x28
	private CharacterInfoTalentUnlockView _unlockView; // 0x30
	public Single cacheHeight; // 0x38
	private TextGenerator m_textGenerate; // 0x40
	private CharacterTalentViewModel m_viewModel; // 0x48
	private static DelegateBridge __Hotfix0_GetAndApplyHeight; // 0x0
	private static DelegateBridge __Hotfix0_CalcHeight; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d86a8c VA: 0x759539ea8c
	public override Single GetAndApplyHeight() { }
	// RVA: 0x2d86b20 VA: 0x759539eb20
	public Single CalcHeight() { }
	// RVA: 0x2d83bbc VA: 0x759539bbbc
	public Void Render(CharacterTalentViewModel viewModel) { }
	// RVA: 0x2d86b94 VA: 0x759539eb94
	public Void .ctor() { }
}
```