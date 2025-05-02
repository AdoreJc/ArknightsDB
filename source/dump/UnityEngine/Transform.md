# Transform

**Namespace:** `UnityEngine`


## Properties

- `Vector3 position`

- `Vector3 localPosition`

- `Vector3 eulerAngles`

- `Vector3 localEulerAngles`

- `Vector3 right`

- `Vector3 up`

- `Vector3 forward`

- `Quaternion rotation`

- `Quaternion localRotation`

- `Vector3 localScale`

- `Transform parent`

- `Matrix4x4 worldToLocalMatrix`

- `Matrix4x4 localToWorldMatrix`

- `Transform root`

- `Int32 childCount`

- `Vector3 lossyScale`

- `Boolean hasChanged`

- `Int32 hierarchyCapacity`

- `Int32 hierarchyCount`


## Methods

- `Vector3 get_position()`

- `Void set_position(Vector3)`

- `Vector3 get_localPosition()`

- `Void set_localPosition(Vector3)`

- `Vector3 get_eulerAngles()`

- `Void set_eulerAngles(Vector3)`

- `Vector3 get_localEulerAngles()`

- `Void set_localEulerAngles(Vector3)`

- `Vector3 get_right()`

- `Void set_right(Vector3)`

- `Vector3 get_up()`

- `Void set_up(Vector3)`

- `Vector3 get_forward()`

- `Void set_forward(Vector3)`

- `Quaternion get_rotation()`

- `Void set_rotation(Quaternion)`

- `Quaternion get_localRotation()`

- `Void set_localRotation(Quaternion)`

- `Vector3 get_localScale()`

- `Void set_localScale(Vector3)`

- `Transform get_parent()`

- `Void set_parent(Transform)`

- `Transform GetParent()`

- `Void SetParent(Transform)`

- `Void SetParent(Transform, Boolean)`

- `Matrix4x4 get_worldToLocalMatrix()`

- `Matrix4x4 get_localToWorldMatrix()`

- `Void SetPositionAndRotation(Vector3, Quaternion)`

- `Void SetLocalPositionAndRotation(Vector3, Quaternion)`

- `Void GetPositionAndRotation(out, out)`

- `Void GetLocalPositionAndRotation(out, out)`

- `Void Translate(Vector3, Space)`

- `Void Translate(Vector3)`

- `Void Translate(Single, Single, Single, Space)`

- `Void Translate(Single, Single, Single)`

- `Void Translate(Vector3, Transform)`

- `Void Translate(Single, Single, Single, Transform)`

- `Void Rotate(Vector3, Space)`

- `Void Rotate(Vector3)`

- `Void Rotate(Single, Single, Single, Space)`

- `Void Rotate(Single, Single, Single)`

- `Void Rotate(Vector3, Single, Space)`

- `Void Rotate(Vector3, Single)`

- `Void RotateAround(Vector3, Vector3, Single)`

- `Void LookAt(Transform, Vector3)`

- `Void LookAt(Transform)`

- `Void LookAt(Vector3, Vector3)`

- `Void LookAt(Vector3)`

- `Void Internal_LookAt(Vector3, Vector3)`

- `Vector3 TransformDirection(Vector3)`

- `Vector3 TransformDirection(Single, Single, Single)`

- `Vector3 InverseTransformDirection(Vector3)`

- `Vector3 InverseTransformDirection(Single, Single, Single)`

- `Vector3 TransformVector(Vector3)`

- `Vector3 TransformVector(Single, Single, Single)`

- `Vector3 InverseTransformVector(Vector3)`

- `Vector3 InverseTransformVector(Single, Single, Single)`

- `Vector3 TransformPoint(Vector3)`

- `Vector3 TransformPoint(Single, Single, Single)`

- `Vector3 InverseTransformPoint(Vector3)`

- `Vector3 InverseTransformPoint(Single, Single, Single)`

- `Transform get_root()`

- `Transform GetRoot()`

- `Int32 get_childCount()`

- `Void DetachChildren()`

- `Void SetAsFirstSibling()`

- `Void SetAsLastSibling()`

- `Void SetSiblingIndex(Int32)`

- `Int32 GetSiblingIndex()`

- `Transform Find(String)`

- `Vector3 get_lossyScale()`

- `Boolean IsChildOf(Transform)`

- `Boolean get_hasChanged()`

- `Void set_hasChanged(Boolean)`

- `Transform FindChild(String)`

- `IEnumerator GetEnumerator()`

- `Void RotateAround(Vector3, Single)`

- `Void RotateAroundLocal(Vector3, Single)`

- `Transform GetChild(Int32)`

- `Int32 GetChildCount()`

- `Int32 get_hierarchyCapacity()`

- `Void set_hierarchyCapacity(Int32)`

- `Int32 internal_getHierarchyCapacity()`

- `Void internal_setHierarchyCapacity(Int32)`

- `Int32 get_hierarchyCount()`

- `Int32 internal_getHierarchyCount()`

- `Void SetConstrainProportionsScale(Boolean)`

- `Boolean IsConstrainProportionsScale()`

- `Void get_position_Injected(out)`

- `Void set_position_Injected(ref)`

- `Void get_localPosition_Injected(out)`

- `Void set_localPosition_Injected(ref)`

- `Void GetLocalEulerAngles_Injected(RotationOrder, out)`

- `Void SetLocalEulerAngles_Injected(ref, RotationOrder)`

- `Void SetLocalEulerHint_Injected(ref)`

- `Void get_rotation_Injected(out)`

- `Void set_rotation_Injected(ref)`

- `Void get_localRotation_Injected(out)`

- `Void set_localRotation_Injected(ref)`

- `Void get_localScale_Injected(out)`

- `Void set_localScale_Injected(ref)`

- `Void get_worldToLocalMatrix_Injected(out)`

- `Void get_localToWorldMatrix_Injected(out)`

- `Void SetPositionAndRotation_Injected(ref, ref)`

- `Void SetLocalPositionAndRotation_Injected(ref, ref)`

- `Void RotateAroundInternal_Injected(ref, Single)`

- `Void Internal_LookAt_Injected(ref, ref)`

- `Void TransformDirection_Injected(ref, out)`

- `Void InverseTransformDirection_Injected(ref, out)`

- `Void TransformVector_Injected(ref, out)`

- `Void InverseTransformVector_Injected(ref, out)`

- `Void TransformPoint_Injected(ref, out)`

- `Void InverseTransformPoint_Injected(ref, out)`

- `Void get_lossyScale_Injected(out)`

- `Void RotateAround_Injected(ref, Single)`

- `Void RotateAroundLocal_Injected(ref, Single)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Transform : Component, IEnumerable
{

	public Vector3 position { get; set; }
	public Vector3 localPosition { get; set; }
	public Vector3 eulerAngles { get; set; }
	public Vector3 localEulerAngles { get; set; }
	public Vector3 right { get; set; }
	public Vector3 up { get; set; }
	public Vector3 forward { get; set; }
	public Quaternion rotation { get; set; }
	public Quaternion localRotation { get; set; }
	internal RotationOrder rotationOrder { get; set; }
	public Vector3 localScale { get; set; }
	public Transform parent { get; set; }
	internal Transform parentInternal { get; set; }
	public Matrix4x4 worldToLocalMatrix { get; }
	public Matrix4x4 localToWorldMatrix { get; }
	public Transform root { get; }
	public Int32 childCount { get; }
	public Vector3 lossyScale { get; }
	public Boolean hasChanged { get; set; }
	public Int32 hierarchyCapacity { get; set; }
	public Int32 hierarchyCount { get; }
	internal Boolean constrainProportionsScale { get; set; }

	// RVA: 0x6891a9c VA: 0x7598ea9a9c
	protected Void .ctor() { }
	// RVA: 0x6891b98 VA: 0x7598ea9b98
	public Vector3 get_position() { }
	// RVA: 0x6891c38 VA: 0x7598ea9c38
	public Void set_position(Vector3 value) { }
	// RVA: 0x6890cc4 VA: 0x7598ea8cc4
	public Vector3 get_localPosition() { }
	// RVA: 0x6890d50 VA: 0x7598ea8d50
	public Void set_localPosition(Vector3 value) { }
	// RVA: 0x6891d58 VA: 0x7598ea9d58
	internal Vector3 GetLocalEulerAngles(RotationOrder order) { }
	// RVA: 0x6891e10 VA: 0x7598ea9e10
	internal Void SetLocalEulerAngles(Vector3 euler, RotationOrder order) { }
	// RVA: 0x6891ec0 VA: 0x7598ea9ec0
	internal Void SetLocalEulerHint(Vector3 euler) { }
	// RVA: 0x6891f58 VA: 0x7598ea9f58
	public Vector3 get_eulerAngles() { }
	// RVA: 0x6891fe0 VA: 0x7598ea9fe0
	public Void set_eulerAngles(Vector3 value) { }
	// RVA: 0x6892064 VA: 0x7598eaa064
	public Vector3 get_localEulerAngles() { }
	// RVA: 0x68920ec VA: 0x7598eaa0ec
	public Void set_localEulerAngles(Vector3 value) { }
	// RVA: 0x6892170 VA: 0x7598eaa170
	public Vector3 get_right() { }
	// RVA: 0x68921ec VA: 0x7598eaa1ec
	public Void set_right(Vector3 value) { }
	// RVA: 0x6892270 VA: 0x7598eaa270
	public Vector3 get_up() { }
	// RVA: 0x68922ec VA: 0x7598eaa2ec
	public Void set_up(Vector3 value) { }
	// RVA: 0x6892370 VA: 0x7598eaa370
	public Vector3 get_forward() { }
	// RVA: 0x68923ec VA: 0x7598eaa3ec
	public Void set_forward(Vector3 value) { }
	// RVA: 0x6891f88 VA: 0x7598ea9f88
	public Quaternion get_rotation() { }
	// RVA: 0x6892010 VA: 0x7598eaa010
	public Void set_rotation(Quaternion value) { }
	// RVA: 0x6892094 VA: 0x7598eaa094
	public Quaternion get_localRotation() { }
	// RVA: 0x689211c VA: 0x7598eaa11c
	public Void set_localRotation(Quaternion value) { }
	// RVA: 0x6892518 VA: 0x7598eaa518
	internal RotationOrder get_rotationOrder() { }
	// RVA: 0x6892590 VA: 0x7598eaa590
	internal Void set_rotationOrder(RotationOrder value) { }
	// RVA: 0x6892554 VA: 0x7598eaa554
	internal Int32 GetRotationOrderInternal() { }
	// RVA: 0x68925d4 VA: 0x7598eaa5d4
	internal Void SetRotationOrderInternal(RotationOrder rotationOrder) { }
	// RVA: 0x6892618 VA: 0x7598eaa618
	public Vector3 get_localScale() { }
	// RVA: 0x68926b8 VA: 0x7598eaa6b8
	public Void set_localScale(Vector3 value) { }
	// RVA: 0x6891a5c VA: 0x7598ea9a5c
	public Transform get_parent() { }
	// RVA: 0x689278c VA: 0x7598eaa78c
	public Void set_parent(Transform value) { }
	// RVA: 0x6892750 VA: 0x7598eaa750
	internal Transform get_parentInternal() { }
	// RVA: 0x6892858 VA: 0x7598eaa858
	internal Void set_parentInternal(Transform value) { }
	// RVA: 0x68928a0 VA: 0x7598eaa8a0
	private Transform GetParent() { }
	// RVA: 0x68928dc VA: 0x7598eaa8dc
	public Void SetParent(Transform p) { }
	// RVA: 0x6892924 VA: 0x7598eaa924
	public Void SetParent(Transform parent, Boolean worldPositionStays) { }
	// RVA: 0x688d518 VA: 0x7598ea5518
	public Matrix4x4 get_worldToLocalMatrix() { }
	// RVA: 0x688dfb0 VA: 0x7598ea5fb0
	public Matrix4x4 get_localToWorldMatrix() { }
	// RVA: 0x6892a00 VA: 0x7598eaaa00
	public Void SetPositionAndRotation(Vector3 position, Quaternion rotation) { }
	// RVA: 0x6892ab4 VA: 0x7598eaaab4
	public Void SetLocalPositionAndRotation(Vector3 localPosition, Quaternion localRotation) { }
	// RVA: 0x6892b68 VA: 0x7598eaab68
	public Void GetPositionAndRotation(out Vector3 position, out Quaternion rotation) { }
	// RVA: 0x6892bbc VA: 0x7598eaabbc
	public Void GetLocalPositionAndRotation(out Vector3 localPosition, out Quaternion localRotation) { }
	// RVA: 0x6892c10 VA: 0x7598eaac10
	public Void Translate(Vector3 translation, Space relativeTo) { }
	// RVA: 0x6892d00 VA: 0x7598eaad00
	public Void Translate(Vector3 translation) { }
	// RVA: 0x6892d08 VA: 0x7598eaad08
	public Void Translate(Single x, Single y, Single z, Space relativeTo) { }
	// RVA: 0x6892d0c VA: 0x7598eaad0c
	public Void Translate(Single x, Single y, Single z) { }
	// RVA: 0x6892d14 VA: 0x7598eaad14
	public Void Translate(Vector3 translation, Transform relativeTo) { }
	// RVA: 0x6892df4 VA: 0x7598eaadf4
	public Void Translate(Single x, Single y, Single z, Transform relativeTo) { }
	// RVA: 0x6892df8 VA: 0x7598eaadf8
	public Void Rotate(Vector3 eulers, Space relativeTo) { }
	// RVA: 0x6893080 VA: 0x7598eab080
	public Void Rotate(Vector3 eulers) { }
	// RVA: 0x6893088 VA: 0x7598eab088
	public Void Rotate(Single xAngle, Single yAngle, Single zAngle, Space relativeTo) { }
	// RVA: 0x689308c VA: 0x7598eab08c
	public Void Rotate(Single xAngle, Single yAngle, Single zAngle) { }
	// RVA: 0x6893094 VA: 0x7598eab094
	internal Void RotateAroundInternal(Vector3 axis, Single angle) { }
	// RVA: 0x689314c VA: 0x7598eab14c
	public Void Rotate(Vector3 axis, Single angle, Space relativeTo) { }
	// RVA: 0x68931fc VA: 0x7598eab1fc
	public Void Rotate(Vector3 axis, Single angle) { }
	// RVA: 0x6893204 VA: 0x7598eab204
	public Void RotateAround(Vector3 point, Vector3 axis, Single angle) { }
	// RVA: 0x68932c8 VA: 0x7598eab2c8
	public Void LookAt(Transform target, Vector3 worldUp) { }
	// RVA: 0x6893388 VA: 0x7598eab388
	public Void LookAt(Transform target) { }
	// RVA: 0x6893384 VA: 0x7598eab384
	public Void LookAt(Vector3 worldPosition, Vector3 worldUp) { }
	// RVA: 0x68934dc VA: 0x7598eab4dc
	public Void LookAt(Vector3 worldPosition) { }
	// RVA: 0x689347c VA: 0x7598eab47c
	private Void Internal_LookAt(Vector3 worldPosition, Vector3 worldUp) { }
	// RVA: 0x6892c98 VA: 0x7598eaac98
	public Vector3 TransformDirection(Vector3 direction) { }
	// RVA: 0x6893600 VA: 0x7598eab600
	public Vector3 TransformDirection(Single x, Single y, Single z) { }
	// RVA: 0x6893604 VA: 0x7598eab604
	public Vector3 InverseTransformDirection(Vector3 direction) { }
	// RVA: 0x68936c0 VA: 0x7598eab6c0
	public Vector3 InverseTransformDirection(Single x, Single y, Single z) { }
	// RVA: 0x68936c4 VA: 0x7598eab6c4
	public Vector3 TransformVector(Vector3 vector) { }
	// RVA: 0x6893780 VA: 0x7598eab780
	public Vector3 TransformVector(Single x, Single y, Single z) { }
	// RVA: 0x6893784 VA: 0x7598eab784
	public Vector3 InverseTransformVector(Vector3 vector) { }
	// RVA: 0x6893840 VA: 0x7598eab840
	public Vector3 InverseTransformVector(Single x, Single y, Single z) { }
	// RVA: 0x6893844 VA: 0x7598eab844
	public Vector3 TransformPoint(Vector3 position) { }
	// RVA: 0x6893900 VA: 0x7598eab900
	public Vector3 TransformPoint(Single x, Single y, Single z) { }
	// RVA: 0x6893904 VA: 0x7598eab904
	public Vector3 InverseTransformPoint(Vector3 position) { }
	// RVA: 0x68939c0 VA: 0x7598eab9c0
	public Vector3 InverseTransformPoint(Single x, Single y, Single z) { }
	// RVA: 0x68939c4 VA: 0x7598eab9c4
	public Transform get_root() { }
	// RVA: 0x6893a00 VA: 0x7598eaba00
	private Transform GetRoot() { }
	// RVA: 0x6893a3c VA: 0x7598eaba3c
	public Int32 get_childCount() { }
	// RVA: 0x6893a78 VA: 0x7598eaba78
	public Void DetachChildren() { }
	// RVA: 0x6893ab4 VA: 0x7598eabab4
	public Void SetAsFirstSibling() { }
	// RVA: 0x6893af0 VA: 0x7598eabaf0
	public Void SetAsLastSibling() { }
	// RVA: 0x6893b2c VA: 0x7598eabb2c
	public Void SetSiblingIndex(Int32 index) { }
	// RVA: 0x6893b70 VA: 0x7598eabb70
	internal Void MoveAfterSibling(Transform transform, Boolean notifyEditorAndMarkDirty) { }
	// RVA: 0x6893bc4 VA: 0x7598eabbc4
	public Int32 GetSiblingIndex() { }
	// RVA: 0x6893c00 VA: 0x7598eabc00
	private static Transform FindRelativeTransformWithPath(Transform transform, String path, Boolean isActiveOnly) { }
	// RVA: 0x6893c54 VA: 0x7598eabc54
	public Transform Find(String n) { }
	// RVA: 0x6893cec VA: 0x7598eabcec
	internal Void SendTransformChangedScale() { }
	// RVA: 0x6893d28 VA: 0x7598eabd28
	public Vector3 get_lossyScale() { }
	// RVA: 0x688be18 VA: 0x7598ea3e18
	public Boolean IsChildOf(Transform parent) { }
	// RVA: 0x6893dc8 VA: 0x7598eabdc8
	public Boolean get_hasChanged() { }
	// RVA: 0x6893e04 VA: 0x7598eabe04
	public Void set_hasChanged(Boolean value) { }
	// RVA: 0x6893e48 VA: 0x7598eabe48
	public Transform FindChild(String n) { }
	// RVA: 0x6893e4c VA: 0x7598eabe4c
	public IEnumerator GetEnumerator() { }
	// RVA: 0x6893efc VA: 0x7598eabefc
	public Void RotateAround(Vector3 axis, Single angle) { }
	// RVA: 0x6893fb4 VA: 0x7598eabfb4
	public Void RotateAroundLocal(Vector3 axis, Single angle) { }
	// RVA: 0x689406c VA: 0x7598eac06c
	public Transform GetChild(Int32 index) { }
	// RVA: 0x68940b0 VA: 0x7598eac0b0
	public Int32 GetChildCount() { }
	// RVA: 0x68940ec VA: 0x7598eac0ec
	public Int32 get_hierarchyCapacity() { }
	// RVA: 0x6894164 VA: 0x7598eac164
	public Void set_hierarchyCapacity(Int32 value) { }
	// RVA: 0x6894128 VA: 0x7598eac128
	private Int32 internal_getHierarchyCapacity() { }
	// RVA: 0x68941a8 VA: 0x7598eac1a8
	private Void internal_setHierarchyCapacity(Int32 value) { }
	// RVA: 0x68941ec VA: 0x7598eac1ec
	public Int32 get_hierarchyCount() { }
	// RVA: 0x6894228 VA: 0x7598eac228
	private Int32 internal_getHierarchyCount() { }
	// RVA: 0x6894264 VA: 0x7598eac264
	internal Boolean IsNonUniformScaleTransform() { }
	// RVA: 0x68942a0 VA: 0x7598eac2a0
	internal Boolean get_constrainProportionsScale() { }
	// RVA: 0x6894318 VA: 0x7598eac318
	internal Void set_constrainProportionsScale(Boolean value) { }
	// RVA: 0x689435c VA: 0x7598eac35c
	private Void SetConstrainProportionsScale(Boolean isLinked) { }
	// RVA: 0x68942dc VA: 0x7598eac2dc
	private Boolean IsConstrainProportionsScale() { }
	// RVA: 0x6891bf4 VA: 0x7598ea9bf4
	private Void get_position_Injected(out Vector3 ret) { }
	// RVA: 0x6891c8c VA: 0x7598ea9c8c
	private Void set_position_Injected(ref Vector3 value) { }
	// RVA: 0x6891cd0 VA: 0x7598ea9cd0
	private Void get_localPosition_Injected(out Vector3 ret) { }
	// RVA: 0x6891d14 VA: 0x7598ea9d14
	private Void set_localPosition_Injected(ref Vector3 value) { }
	// RVA: 0x6891dbc VA: 0x7598ea9dbc
	private Void GetLocalEulerAngles_Injected(RotationOrder order, out Vector3 ret) { }
	// RVA: 0x6891e6c VA: 0x7598ea9e6c
	private Void SetLocalEulerAngles_Injected(ref Vector3 euler, RotationOrder order) { }
	// RVA: 0x6891f14 VA: 0x7598ea9f14
	private Void SetLocalEulerHint_Injected(ref Vector3 euler) { }
	// RVA: 0x6892408 VA: 0x7598eaa408
	private Void get_rotation_Injected(out Quaternion ret) { }
	// RVA: 0x689244c VA: 0x7598eaa44c
	private Void set_rotation_Injected(ref Quaternion value) { }
	// RVA: 0x6892490 VA: 0x7598eaa490
	private Void get_localRotation_Injected(out Quaternion ret) { }
	// RVA: 0x68924d4 VA: 0x7598eaa4d4
	private Void set_localRotation_Injected(ref Quaternion value) { }
	// RVA: 0x6892674 VA: 0x7598eaa674
	private Void get_localScale_Injected(out Vector3 ret) { }
	// RVA: 0x689270c VA: 0x7598eaa70c
	private Void set_localScale_Injected(ref Vector3 value) { }
	// RVA: 0x6892978 VA: 0x7598eaa978
	private Void get_worldToLocalMatrix_Injected(out Matrix4x4 ret) { }
	// RVA: 0x68929bc VA: 0x7598eaa9bc
	private Void get_localToWorldMatrix_Injected(out Matrix4x4 ret) { }
	// RVA: 0x6892a60 VA: 0x7598eaaa60
	private Void SetPositionAndRotation_Injected(ref Vector3 position, ref Quaternion rotation) { }
	// RVA: 0x6892b14 VA: 0x7598eaab14
	private Void SetLocalPositionAndRotation_Injected(ref Vector3 localPosition, ref Quaternion localRotation) { }
	// RVA: 0x68930f8 VA: 0x7598eab0f8
	private Void RotateAroundInternal_Injected(ref Vector3 axis, Single angle) { }
	// RVA: 0x6893558 VA: 0x7598eab558
	private Void Internal_LookAt_Injected(ref Vector3 worldPosition, ref Vector3 worldUp) { }
	// RVA: 0x68935ac VA: 0x7598eab5ac
	private Void TransformDirection_Injected(ref Vector3 direction, out Vector3 ret) { }
	// RVA: 0x689366c VA: 0x7598eab66c
	private Void InverseTransformDirection_Injected(ref Vector3 direction, out Vector3 ret) { }
	// RVA: 0x689372c VA: 0x7598eab72c
	private Void TransformVector_Injected(ref Vector3 vector, out Vector3 ret) { }
	// RVA: 0x68937ec VA: 0x7598eab7ec
	private Void InverseTransformVector_Injected(ref Vector3 vector, out Vector3 ret) { }
	// RVA: 0x68938ac VA: 0x7598eab8ac
	private Void TransformPoint_Injected(ref Vector3 position, out Vector3 ret) { }
	// RVA: 0x689396c VA: 0x7598eab96c
	private Void InverseTransformPoint_Injected(ref Vector3 position, out Vector3 ret) { }
	// RVA: 0x6893d84 VA: 0x7598eabd84
	private Void get_lossyScale_Injected(out Vector3 ret) { }
	// RVA: 0x6893f60 VA: 0x7598eabf60
	private Void RotateAround_Injected(ref Vector3 axis, Single angle) { }
	// RVA: 0x6894018 VA: 0x7598eac018
	private Void RotateAroundLocal_Injected(ref Vector3 axis, Single angle) { }
}
```