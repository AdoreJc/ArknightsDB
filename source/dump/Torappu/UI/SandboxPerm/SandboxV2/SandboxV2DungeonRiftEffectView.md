# SandboxV2DungeonRiftEffectView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _objGlobalEffects`

- `Text _txtGlobalEffectTitle`

- `Text _txtGlobalEffectDesc`

- `GameObject _objDifficulty`

- `Text _txtDifficultyTitle`

- `Text _txtDifficultyLv`

- `Text _txtDifficultyDesc`

- `GameObject _objTeam`

- `Text _txtTeamTitle`

- `Text _txtTeamLv`

- `Text _txtTeamDesc`

- `Boolean m_isInited`


## Methods

- `Void Render(SandboxV2DungeonMiscRiftViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonRiftEffectView : MonoBehaviour, IHotfixable
{
	private GameObject _objGlobalEffects; // 0x18
	private Text _txtGlobalEffectTitle; // 0x20
	private Text _txtGlobalEffectDesc; // 0x28
	private GameObject _objDifficulty; // 0x30
	private Text _txtDifficultyTitle; // 0x38
	private Text _txtDifficultyLv; // 0x40
	private Text _txtDifficultyDesc; // 0x48
	private GameObject _objTeam; // 0x50
	private Text _txtTeamTitle; // 0x58
	private Text _txtTeamLv; // 0x60
	private Text _txtTeamDesc; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x254c604 VA: 0x7594b64604
	public Void Render(SandboxV2DungeonMiscRiftViewModel viewModel) { }
	// RVA: 0x254c818 VA: 0x7594b64818
	private Void _InitIfNot() { }
	// RVA: 0x254c90c VA: 0x7594b6490c
	public Void .ctor() { }
}
```