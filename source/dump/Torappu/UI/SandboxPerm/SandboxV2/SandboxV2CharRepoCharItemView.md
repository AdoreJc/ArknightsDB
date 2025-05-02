# SandboxV2CharRepoCharItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _emptySkillGo`

- `GameObject _detailSkillGo`

- `Image _imgSkill`

- `GameObject _emptyEquipGo`

- `GameObject _detailEquipGo`

- `Image _imgEquipIcon`


## Methods

- `Void _RenderCharSkillAndEquipInfo(SandboxV2CharViewModel)`

- `Void <>xLuaBaseProxy_Render(Int32, SandboxV2CharViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharRepoCharItemView : SandboxV2CharRepoAbstractItemView
{
	private GameObject _emptySkillGo; // 0x110
	private GameObject _detailSkillGo; // 0x118
	private Image _imgSkill; // 0x120
	private GameObject _emptyEquipGo; // 0x128
	private GameObject _detailEquipGo; // 0x130
	private Image _imgEquipIcon; // 0x138
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderCharSkillAndEquipInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x260bc7c VA: 0x7594c23c7c
	public override Void Render(Int32 position, SandboxV2CharViewModel charModel, Boolean isCookClickable) { }
	// RVA: 0x260bd44 VA: 0x7594c23d44
	private Void _RenderCharSkillAndEquipInfo(SandboxV2CharViewModel charModel) { }
	// RVA: 0x260bf4c VA: 0x7594c23f4c
	public Void .ctor() { }
	// RVA: 0x260bfb8 VA: 0x7594c23fb8
	private Void <>xLuaBaseProxy_Render(Int32 P0, SandboxV2CharViewModel P1, Boolean P2) { }
}
```