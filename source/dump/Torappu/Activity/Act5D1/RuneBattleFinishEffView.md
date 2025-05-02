# RuneBattleFinishEffView

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `UIBlurFloatPanel _backImage`

- `Image _spriteLogo`

- `Text _stageName`

- `Text _stageDesc`

- `Text _runeValue`

- `ParticleSystem _psItem`

- `Boolean m_effectEndFlag`

- `Boolean m_isClosed`


## Properties

- `Boolean EffectEndFlag`

- `Boolean IsClosed`


## Methods

- `Boolean get_EffectEndFlag()`

- `Void set_EffectEndFlag(Boolean)`

- `Boolean get_IsClosed()`

- `Void set_IsClosed(Boolean)`

- `Void Init(RuneBattleFinishStateBean)`

- `IEnumerator PlayEffect()`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class RuneBattleFinishEffView : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _backImage; // 0x18
	private Image _spriteLogo; // 0x20
	private Text _stageName; // 0x28
	private Text _stageDesc; // 0x30
	private Text _runeValue; // 0x38
	private ParticleSystem _psItem; // 0x40
	private Boolean m_effectEndFlag; // 0x48
	private Boolean m_isClosed; // 0x49
	private const Single PASTTIME; // 0x0
	private static DelegateBridge __Hotfix0_get_EffectEndFlag; // 0x0
	private static DelegateBridge __Hotfix0_set_EffectEndFlag; // 0x8
	private static DelegateBridge __Hotfix0_get_IsClosed; // 0x10
	private static DelegateBridge __Hotfix0_set_IsClosed; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_PlayEffect; // 0x28
	private static DelegateBridge __Hotfix0_Hide; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean EffectEndFlag { get; set; }
	public Boolean IsClosed { get; set; }

	// RVA: 0x31c762c VA: 0x75957df62c
	public Boolean get_EffectEndFlag() { }
	// RVA: 0x31c73a8 VA: 0x75957df3a8
	public Void set_EffectEndFlag(Boolean value) { }
	// RVA: 0x31c7868 VA: 0x75957df868
	public Boolean get_IsClosed() { }
	// RVA: 0x31c7428 VA: 0x75957df428
	public Void set_IsClosed(Boolean value) { }
	// RVA: 0x31c71b4 VA: 0x75957df1b4
	public Void Init(RuneBattleFinishStateBean stateBean) { }
	// RVA: 0x31c72fc VA: 0x75957df2fc
	public IEnumerator PlayEffect() { }
	// RVA: 0x31c93c8 VA: 0x75957e13c8
	public Void Hide() { }
	// RVA: 0x31c9454 VA: 0x75957e1454
	public Void .ctor() { }
}
```