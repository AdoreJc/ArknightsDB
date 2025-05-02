# Avatar

**Namespace:** `UnityEngine`


## Properties

- `Boolean isValid`

- `Boolean isHuman`

- `HumanDescription humanDescription`


## Methods

- `Boolean get_isValid()`

- `Boolean get_isHuman()`

- `HumanDescription get_humanDescription()`

- `Void get_humanDescription_Injected(out)`

- `Void Internal_GetPreRotation_Injected(Int32, out)`

- `Void Internal_GetPostRotation_Injected(Int32, out)`

- `Void Internal_GetZYPostQ_Injected(Int32, ref, ref, out)`

- `Void Internal_GetZYRoll_Injected(Int32, ref, out)`

- `Void Internal_GetLimitSign_Injected(Int32, out)`


## Dump
```C#
// Dll : UnityEngine.AnimationModule.dll
// Namespace : UnityEngine
public class Avatar : Object
{

	public Boolean isValid { get; }
	public Boolean isHuman { get; }
	public HumanDescription humanDescription { get; }

	// RVA: 0x6848d70 VA: 0x7598e60d70
	private Void .ctor() { }
	// RVA: 0x6848dc8 VA: 0x7598e60dc8
	public Boolean get_isValid() { }
	// RVA: 0x6848e04 VA: 0x7598e60e04
	public Boolean get_isHuman() { }
	// RVA: 0x6848e40 VA: 0x7598e60e40
	public HumanDescription get_humanDescription() { }
	// RVA: 0x6848ef0 VA: 0x7598e60ef0
	internal Void SetMuscleMinMax(Int32 muscleId, Single min, Single max) { }
	// RVA: 0x6848f4c VA: 0x7598e60f4c
	internal Void SetParameter(Int32 parameterId, Single value) { }
	// RVA: 0x6848fa0 VA: 0x7598e60fa0
	internal Single GetAxisLength(Int32 humanId) { }
	// RVA: 0x6849090 VA: 0x7598e61090
	internal Quaternion GetPreRotation(Int32 humanId) { }
	// RVA: 0x684913c VA: 0x7598e6113c
	internal Quaternion GetPostRotation(Int32 humanId) { }
	// RVA: 0x68491e8 VA: 0x7598e611e8
	internal Quaternion GetZYPostQ(Int32 humanId, Quaternion parentQ, Quaternion q) { }
	// RVA: 0x684930c VA: 0x7598e6130c
	internal Quaternion GetZYRoll(Int32 humanId, Vector3 uvw) { }
	// RVA: 0x68493ec VA: 0x7598e613ec
	internal Vector3 GetLimitSign(Int32 humanId) { }
	// RVA: 0x684904c VA: 0x7598e6104c
	internal Single Internal_GetAxisLength(Int32 humanId) { }
	// RVA: 0x68490dc VA: 0x7598e610dc
	internal Quaternion Internal_GetPreRotation(Int32 humanId) { }
	// RVA: 0x6849188 VA: 0x7598e61188
	internal Quaternion Internal_GetPostRotation(Int32 humanId) { }
	// RVA: 0x6849294 VA: 0x7598e61294
	internal Quaternion Internal_GetZYPostQ(Int32 humanId, Quaternion parentQ, Quaternion q) { }
	// RVA: 0x6849380 VA: 0x7598e61380
	internal Quaternion Internal_GetZYRoll(Int32 humanId, Vector3 uvw) { }
	// RVA: 0x6849438 VA: 0x7598e61438
	internal Vector3 Internal_GetLimitSign(Int32 humanId) { }
	// RVA: 0x6848eac VA: 0x7598e60eac
	private Void get_humanDescription_Injected(out HumanDescription ret) { }
	// RVA: 0x684949c VA: 0x7598e6149c
	private Void Internal_GetPreRotation_Injected(Int32 humanId, out Quaternion ret) { }
	// RVA: 0x68494f0 VA: 0x7598e614f0
	private Void Internal_GetPostRotation_Injected(Int32 humanId, out Quaternion ret) { }
	// RVA: 0x6849544 VA: 0x7598e61544
	private Void Internal_GetZYPostQ_Injected(Int32 humanId, ref Quaternion parentQ, ref Quaternion q, out Quaternion ret) { }
	// RVA: 0x68495b0 VA: 0x7598e615b0
	private Void Internal_GetZYRoll_Injected(Int32 humanId, ref Vector3 uvw, out Quaternion ret) { }
	// RVA: 0x684960c VA: 0x7598e6160c
	private Void Internal_GetLimitSign_Injected(Int32 humanId, out Vector3 ret) { }
}
```