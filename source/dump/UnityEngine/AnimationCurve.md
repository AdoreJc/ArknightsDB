# AnimationCurve

**Namespace:** `UnityEngine`


## Properties

- `Keyframe Item`

- `Int32 length`

- `WrapMode preWrapMode`

- `WrapMode postWrapMode`


## Methods

- `Boolean Internal_Equals(IntPtr)`

- `Single Evaluate(Single)`

- `Void set_keys(Keyframe[])`

- `Int32 AddKey(Single, Single)`

- `Int32 AddKey(Keyframe)`

- `Int32 AddKey_Internal(Keyframe)`

- `Int32 MoveKey(Int32, Keyframe)`

- `Void RemoveKey(Int32)`

- `Keyframe get_Item(Int32)`

- `Int32 get_length()`

- `Void SetKeys(Keyframe[])`

- `Keyframe GetKey(Int32)`

- `Void SmoothTangents(Int32, Single)`

- `WrapMode get_preWrapMode()`

- `Void set_preWrapMode(WrapMode)`

- `WrapMode get_postWrapMode()`

- `Void set_postWrapMode(WrapMode)`

- `Boolean Equals(AnimationCurve)`

- `Int32 AddKey_Internal_Injected(ref)`

- `Int32 MoveKey_Injected(Int32, ref)`

- `Void GetKey_Injected(Int32, out)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class AnimationCurve : IEquatable`1
{
	internal IntPtr m_Ptr; // 0x10

	public Keyframe[] keys { get; set; }
	public Keyframe Item { get; }
	public Int32 length { get; }
	public WrapMode preWrapMode { get; set; }
	public WrapMode postWrapMode { get; set; }

	// RVA: 0x684fdbc VA: 0x7598e67dbc
	private static Void Internal_Destroy(IntPtr ptr) { }
	// RVA: 0x684fdf8 VA: 0x7598e67df8
	private static IntPtr Internal_Create(Keyframe[] keys) { }
	// RVA: 0x684fe34 VA: 0x7598e67e34
	private Boolean Internal_Equals(IntPtr other) { }
	// RVA: 0x684fe78 VA: 0x7598e67e78
	protected override Void Finalize() { }
	// RVA: 0x684ff34 VA: 0x7598e67f34
	public Single Evaluate(Single time) { }
	// RVA: 0x684ff80 VA: 0x7598e67f80
	public Keyframe[] get_keys() { }
	// RVA: 0x684fff8 VA: 0x7598e67ff8
	public Void set_keys(Keyframe[] value) { }
	// RVA: 0x6850080 VA: 0x7598e68080
	public Int32 AddKey(Single time, Single value) { }
	// RVA: 0x68500d4 VA: 0x7598e680d4
	public Int32 AddKey(Keyframe key) { }
	// RVA: 0x6850130 VA: 0x7598e68130
	private Int32 AddKey_Internal(Keyframe key) { }
	// RVA: 0x68501b8 VA: 0x7598e681b8
	public Int32 MoveKey(Int32 index, Keyframe key) { }
	// RVA: 0x6850260 VA: 0x7598e68260
	public Void RemoveKey(Int32 index) { }
	// RVA: 0x68502a4 VA: 0x7598e682a4
	public Keyframe get_Item(Int32 index) { }
	// RVA: 0x68503b8 VA: 0x7598e683b8
	public Int32 get_length() { }
	// RVA: 0x685003c VA: 0x7598e6803c
	private Void SetKeys(Keyframe[] keys) { }
	// RVA: 0x685033c VA: 0x7598e6833c
	private Keyframe GetKey(Int32 index) { }
	// RVA: 0x684ffbc VA: 0x7598e67fbc
	private Keyframe[] GetKeys() { }
	// RVA: 0x6850448 VA: 0x7598e68448
	public Void SmoothTangents(Int32 index, Single weight) { }
	// RVA: 0x685049c VA: 0x7598e6849c
	public static AnimationCurve Constant(Single timeStart, Single timeEnd, Single value) { }
	// RVA: 0x68504ac VA: 0x7598e684ac
	public static AnimationCurve Linear(Single timeStart, Single valueStart, Single timeEnd, Single valueEnd) { }
	// RVA: 0x685063c VA: 0x7598e6863c
	public static AnimationCurve EaseInOut(Single timeStart, Single valueStart, Single timeEnd, Single valueEnd) { }
	// RVA: 0x6850770 VA: 0x7598e68770
	public WrapMode get_preWrapMode() { }
	// RVA: 0x68507ac VA: 0x7598e687ac
	public Void set_preWrapMode(WrapMode value) { }
	// RVA: 0x68507f0 VA: 0x7598e687f0
	public WrapMode get_postWrapMode() { }
	// RVA: 0x685082c VA: 0x7598e6882c
	public Void set_postWrapMode(WrapMode value) { }
	// RVA: 0x68505ec VA: 0x7598e685ec
	public Void .ctor(Keyframe[] keys) { }
	// RVA: 0x6850870 VA: 0x7598e68870
	public Void .ctor() { }
	// RVA: 0x68508bc VA: 0x7598e688bc
	public override Boolean Equals(Object o) { }
	// RVA: 0x6850984 VA: 0x7598e68984
	public Boolean Equals(AnimationCurve other) { }
	// RVA: 0x6850a4c VA: 0x7598e68a4c
	public override Int32 GetHashCode() { }
	// RVA: 0x6850174 VA: 0x7598e68174
	private Int32 AddKey_Internal_Injected(ref Keyframe key) { }
	// RVA: 0x685020c VA: 0x7598e6820c
	private Int32 MoveKey_Injected(Int32 index, ref Keyframe key) { }
	// RVA: 0x68503f4 VA: 0x7598e683f4
	private Void GetKey_Injected(Int32 index, out Keyframe ret) { }
}
```