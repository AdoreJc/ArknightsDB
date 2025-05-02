# Animator

**Namespace:** `UnityEngine`


## Properties

- `Boolean isHuman`

- `Boolean hasRootMotion`

- `AnimatorUpdateMode updateMode`

- `Int32 layerCount`

- `Int32 parameterCount`

- `Single speed`

- `RuntimeAnimatorController runtimeAnimatorController`

- `Boolean hasBoundPlayables`

- `Avatar avatar`


## Methods

- `Boolean get_isHuman()`

- `Boolean get_hasRootMotion()`

- `Void SetFloat(String, Single)`

- `Void SetBool(String, Boolean)`

- `Void SetBool(Int32, Boolean)`

- `Void SetInteger(String, Int32)`

- `Void SetInteger(Int32, Int32)`

- `Void SetTrigger(String)`

- `Void SetTrigger(Int32)`

- `Void ResetTrigger(String)`

- `Void set_updateMode(AnimatorUpdateMode)`

- `Int32 get_layerCount()`

- `String GetLayerName(Int32)`

- `Single GetLayerWeight(Int32)`

- `Void GetAnimatorStateInfo(Int32, StateInfoIndex, out)`

- `AnimatorStateInfo GetCurrentAnimatorStateInfo(Int32)`

- `AnimatorStateInfo GetNextAnimatorStateInfo(Int32)`

- `Int32 GetCurrentAnimatorClipInfoCount(Int32)`

- `Int32 GetNextAnimatorClipInfoCount(Int32)`

- `Void GetCurrentAnimatorClipInfo(Int32, List`1)`

- `Void GetAnimatorClipInfoInternal(Int32, Boolean, Object)`

- `Void GetNextAnimatorClipInfo(Int32, List`1)`

- `Boolean IsInTransition(Int32)`

- `Int32 get_parameterCount()`

- `Void set_speed(Single)`

- `Void Play(String)`

- `Void Play(String, Int32, Single)`

- `Void Play(Int32, Int32, Single)`

- `Void Play(Int32)`

- `RuntimeAnimatorController get_runtimeAnimatorController()`

- `Boolean get_hasBoundPlayables()`

- `Avatar get_avatar()`

- `Void SetFloatString(String, Single)`

- `Void SetBoolString(String, Boolean)`

- `Void SetBoolID(Int32, Boolean)`

- `Void SetIntegerString(String, Int32)`

- `Void SetIntegerID(Int32, Int32)`

- `Void SetTriggerString(String)`

- `Void SetTriggerID(Int32)`

- `Void ResetTriggerString(String)`

- `Void Update(Single)`

- `Void Rebind()`

- `Void Rebind(Boolean)`


## Dump
```C#
// Dll : UnityEngine.AnimationModule.dll
// Namespace : UnityEngine
public class Animator : Behaviour
{

	public Boolean isHuman { get; }
	public Boolean hasRootMotion { get; }
	public AnimatorUpdateMode updateMode { set; }
	public Int32 layerCount { get; }
	public AnimatorControllerParameter[] parameters { get; }
	public Int32 parameterCount { get; }
	public Single speed { set; }
	public RuntimeAnimatorController runtimeAnimatorController { get; }
	public Boolean hasBoundPlayables { get; }
	public Avatar avatar { get; }

	// RVA: 0x6846f28 VA: 0x7598e5ef28
	public Boolean get_isHuman() { }
	// RVA: 0x6846f64 VA: 0x7598e5ef64
	public Boolean get_hasRootMotion() { }
	// RVA: 0x6846fa0 VA: 0x7598e5efa0
	public Void SetFloat(String name, Single value) { }
	// RVA: 0x6847048 VA: 0x7598e5f048
	public Void SetBool(String name, Boolean value) { }
	// RVA: 0x68470f0 VA: 0x7598e5f0f0
	public Void SetBool(Int32 id, Boolean value) { }
	// RVA: 0x6847198 VA: 0x7598e5f198
	public Void SetInteger(String name, Int32 value) { }
	// RVA: 0x6847240 VA: 0x7598e5f240
	public Void SetInteger(Int32 id, Int32 value) { }
	// RVA: 0x68472e8 VA: 0x7598e5f2e8
	public Void SetTrigger(String name) { }
	// RVA: 0x6847370 VA: 0x7598e5f370
	public Void SetTrigger(Int32 id) { }
	// RVA: 0x68473f8 VA: 0x7598e5f3f8
	public Void ResetTrigger(String name) { }
	// RVA: 0x6847480 VA: 0x7598e5f480
	public Void set_updateMode(AnimatorUpdateMode value) { }
	// RVA: 0x VA: 0x0
	private static T[] ConvertStateMachineBehaviour(ScriptableObject[] rawObjects) { }
	// RVA: 0x VA: 0x0
	public T[] GetBehaviours() { }
	// RVA: 0x68474c4 VA: 0x7598e5f4c4
	internal ScriptableObject[] InternalGetBehaviours(Type type) { }
	// RVA: 0x6847508 VA: 0x7598e5f508
	public Int32 get_layerCount() { }
	// RVA: 0x6847544 VA: 0x7598e5f544
	public String GetLayerName(Int32 layerIndex) { }
	// RVA: 0x6847588 VA: 0x7598e5f588
	public Single GetLayerWeight(Int32 layerIndex) { }
	// RVA: 0x68475cc VA: 0x7598e5f5cc
	private Void GetAnimatorStateInfo(Int32 layerIndex, StateInfoIndex stateInfoIndex, out AnimatorStateInfo info) { }
	// RVA: 0x6847628 VA: 0x7598e5f628
	public AnimatorStateInfo GetCurrentAnimatorStateInfo(Int32 layerIndex) { }
	// RVA: 0x68476a8 VA: 0x7598e5f6a8
	public AnimatorStateInfo GetNextAnimatorStateInfo(Int32 layerIndex) { }
	// RVA: 0x6847728 VA: 0x7598e5f728
	internal Int32 GetAnimatorClipInfoCount(Int32 layerIndex, Boolean current) { }
	// RVA: 0x684777c VA: 0x7598e5f77c
	public Int32 GetCurrentAnimatorClipInfoCount(Int32 layerIndex) { }
	// RVA: 0x68477c4 VA: 0x7598e5f7c4
	public Int32 GetNextAnimatorClipInfoCount(Int32 layerIndex) { }
	// RVA: 0x684780c VA: 0x7598e5f80c
	public AnimatorClipInfo[] GetCurrentAnimatorClipInfo(Int32 layerIndex) { }
	// RVA: 0x6847850 VA: 0x7598e5f850
	public Void GetCurrentAnimatorClipInfo(Int32 layerIndex, List`1 clips) { }
	// RVA: 0x68478f8 VA: 0x7598e5f8f8
	private Void GetAnimatorClipInfoInternal(Int32 layerIndex, Boolean isCurrent, Object clips) { }
	// RVA: 0x6847954 VA: 0x7598e5f954
	public Void GetNextAnimatorClipInfo(Int32 layerIndex, List`1 clips) { }
	// RVA: 0x68479fc VA: 0x7598e5f9fc
	public Boolean IsInTransition(Int32 layerIndex) { }
	// RVA: 0x6847a40 VA: 0x7598e5fa40
	public AnimatorControllerParameter[] get_parameters() { }
	// RVA: 0x6847a7c VA: 0x7598e5fa7c
	public Int32 get_parameterCount() { }
	// RVA: 0x6847ab8 VA: 0x7598e5fab8
	public Void set_speed(Single value) { }
	// RVA: 0x6847b04 VA: 0x7598e5fb04
	public Void Play(String stateName) { }
	// RVA: 0x6847b14 VA: 0x7598e5fb14
	public Void Play(String stateName, Int32 layer, Single normalizedTime) { }
	// RVA: 0x6847ba4 VA: 0x7598e5fba4
	public Void Play(Int32 stateNameHash, Int32 layer, Single normalizedTime) { }
	// RVA: 0x6847c08 VA: 0x7598e5fc08
	public Void Play(Int32 stateNameHash) { }
	// RVA: 0x6847c58 VA: 0x7598e5fc58
	public RuntimeAnimatorController get_runtimeAnimatorController() { }
	// RVA: 0x6847c94 VA: 0x7598e5fc94
	public Boolean get_hasBoundPlayables() { }
	// RVA: 0x6846eb4 VA: 0x7598e5eeb4
	public static Int32 StringToHash(String name) { }
	// RVA: 0x6847cd0 VA: 0x7598e5fcd0
	public Avatar get_avatar() { }
	// RVA: 0x6846ff4 VA: 0x7598e5eff4
	private Void SetFloatString(String name, Single value) { }
	// RVA: 0x684709c VA: 0x7598e5f09c
	private Void SetBoolString(String name, Boolean value) { }
	// RVA: 0x6847144 VA: 0x7598e5f144
	private Void SetBoolID(Int32 id, Boolean value) { }
	// RVA: 0x68471ec VA: 0x7598e5f1ec
	private Void SetIntegerString(String name, Int32 value) { }
	// RVA: 0x6847294 VA: 0x7598e5f294
	private Void SetIntegerID(Int32 id, Int32 value) { }
	// RVA: 0x684732c VA: 0x7598e5f32c
	private Void SetTriggerString(String name) { }
	// RVA: 0x68473b4 VA: 0x7598e5f3b4
	private Void SetTriggerID(Int32 id) { }
	// RVA: 0x684743c VA: 0x7598e5f43c
	private Void ResetTriggerString(String name) { }
	// RVA: 0x6847d0c VA: 0x7598e5fd0c
	public Void Update(Single deltaTime) { }
	// RVA: 0x6847d58 VA: 0x7598e5fd58
	public Void Rebind() { }
	// RVA: 0x6847d98 VA: 0x7598e5fd98
	private Void Rebind(Boolean writeDefaultValues) { }
}
```