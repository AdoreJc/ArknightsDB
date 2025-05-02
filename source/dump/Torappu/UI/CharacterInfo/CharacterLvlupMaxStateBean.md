# CharacterLvlupMaxStateBean

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterIllustViewProperty illustProperty`

- `EvolvePhase evolvePhase`

- `Int32 potentialRank`

- `Int32 currentLevel`

- `Int32 m_charInstId`

- `UplevelAttribute m_originAttr`

- `UplevelAttribute m_currentAttr`

- `String m_powerId`

- `Sprite m_campLogo`


## Properties

- `UplevelAttribute originAttribute`

- `UplevelAttribute currentAttribute`

- `String powerId`

- `Sprite campLogo`


## Methods

- `UplevelAttribute get_originAttribute()`

- `UplevelAttribute get_currentAttribute()`

- `String get_powerId()`

- `Sprite get_campLogo()`

- `Void LoadData(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupMaxStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public CharacterIllustViewProperty illustProperty; // 0x18
	public EvolvePhase evolvePhase; // 0x20
	public Int32 potentialRank; // 0x24
	public Int32 currentLevel; // 0x28
	private Int32 m_charInstId; // 0x2c
	private UplevelAttribute m_originAttr; // 0x30
	private UplevelAttribute m_currentAttr; // 0x40
	private String m_powerId; // 0x50
	private Sprite m_campLogo; // 0x58
	private static DelegateBridge __Hotfix0_get_originAttribute; // 0x0
	private static DelegateBridge __Hotfix0_get_currentAttribute; // 0x8
	private static DelegateBridge __Hotfix0_get_powerId; // 0x10
	private static DelegateBridge __Hotfix0_get_campLogo; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public UplevelAttribute originAttribute { get; }
	public UplevelAttribute currentAttribute { get; }
	public String powerId { get; }
	public Sprite campLogo { get; }

	// RVA: 0x2d5fcc0 VA: 0x7595377cc0
	public UplevelAttribute get_originAttribute() { }
	// RVA: 0x2d5fd24 VA: 0x7595377d24
	public UplevelAttribute get_currentAttribute() { }
	// RVA: 0x2d5fd88 VA: 0x7595377d88
	public String get_powerId() { }
	// RVA: 0x2d5fdf0 VA: 0x7595377df0
	public Sprite get_campLogo() { }
	// RVA: 0x2d5fe58 VA: 0x7595377e58
	public Void LoadData(Int32 charInstId, Int32 originLevel) { }
	// RVA: 0x2d60334 VA: 0x7595378334
	public Void .ctor() { }
}
```