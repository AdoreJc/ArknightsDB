# MiscSettingModifier

**Namespace:** ` `


## Fields

- `Boolean m_dontOccupyDeployCnt`

- `Boolean m_dontOccupyMaxDeployCnt`

- `AdditionalBuildCondition m_additionalBuildCondition`

- `Boolean m_ignoreRespawningState`


## Properties

- `Boolean dontOccupyDeployCnt`

- `Boolean dontOccupyMaxDeployCnt`

- `Boolean ignoreRespawningState`

- `AdditionalBuildCondition additionalBuildCondition`


## Methods

- `Boolean get_dontOccupyDeployCnt()`

- `Boolean get_dontOccupyMaxDeployCnt()`

- `Boolean get_ignoreRespawningState()`

- `AdditionalBuildCondition get_additionalBuildCondition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MiscSettingModifier : CardBuffModifier
{
	private Boolean m_dontOccupyDeployCnt; // 0x15
	private Boolean m_dontOccupyMaxDeployCnt; // 0x16
	private AdditionalBuildCondition m_additionalBuildCondition; // 0x18
	private Boolean m_ignoreRespawningState; // 0x28

	public Boolean dontOccupyDeployCnt { get; }
	public Boolean dontOccupyMaxDeployCnt { get; }
	public Boolean ignoreRespawningState { get; }
	public AdditionalBuildCondition additionalBuildCondition { get; }

	// RVA: 0x3fb4678 VA: 0x75965cc678
	public Void .ctor(Boolean dontOccupyDeployCnt, AdditionalBuildCondition additionalBuildCondition, Boolean ignoreRespawningState, Boolean dontOccupyMaxDeployCnt) { }
	// RVA: 0x3fb46d4 VA: 0x75965cc6d4
	public Boolean get_dontOccupyDeployCnt() { }
	// RVA: 0x3fb46dc VA: 0x75965cc6dc
	public Boolean get_dontOccupyMaxDeployCnt() { }
	// RVA: 0x3fb46e4 VA: 0x75965cc6e4
	public Boolean get_ignoreRespawningState() { }
	// RVA: 0x3fb46ec VA: 0x75965cc6ec
	public AdditionalBuildCondition get_additionalBuildCondition() { }
	// RVA: 0x3fb46f8 VA: 0x75965cc6f8
	public static MiscSettingModifier CreateRuntimeModifier(Blackboard blackboard) { }
	// RVA: 0x3fb493c VA: 0x75965cc93c
	public virtual Boolean IsTriggered(Card card) { }
	// RVA: 0x3fb4944 VA: 0x75965cc944
	public virtual Void Preprocess(Deck deck) { }
	// RVA: 0x3fb4948 VA: 0x75965cc948
	public override Void ApplyFirstPass(Card card, ref CardBuffOptions options) { }
}
```