# PersistentCall

**Namespace:** `UnityEngine.Events`


## Fields

- `Object m_Target`

- `String m_TargetAssemblyTypeName`

- `String m_MethodName`

- `PersistentListenerMode m_Mode`

- `ArgumentCache m_Arguments`

- `UnityEventCallState m_CallState`


## Properties

- `Object target`

- `String targetAssemblyTypeName`

- `String methodName`

- `PersistentListenerMode mode`

- `ArgumentCache arguments`


## Methods

- `Object get_target()`

- `String get_targetAssemblyTypeName()`

- `String get_methodName()`

- `PersistentListenerMode get_mode()`

- `ArgumentCache get_arguments()`

- `Boolean IsValid()`

- `BaseInvokableCall GetRuntimeCall(UnityEventBase)`

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Events
internal class PersistentCall : ISerializationCallbackReceiver
{
	private Object m_Target; // 0x10
	private String m_TargetAssemblyTypeName; // 0x18
	private String m_MethodName; // 0x20
	private PersistentListenerMode m_Mode; // 0x28
	private ArgumentCache m_Arguments; // 0x30
	private UnityEventCallState m_CallState; // 0x38

	public Object target { get; }
	public String targetAssemblyTypeName { get; }
	public String methodName { get; }
	public PersistentListenerMode mode { get; }
	public ArgumentCache arguments { get; }

	// RVA: 0x6896dc4 VA: 0x7598eaedc4
	public Object get_target() { }
	// RVA: 0x6896dcc VA: 0x7598eaedcc
	public String get_targetAssemblyTypeName() { }
	// RVA: 0x6896e84 VA: 0x7598eaee84
	public String get_methodName() { }
	// RVA: 0x6896e8c VA: 0x7598eaee8c
	public PersistentListenerMode get_mode() { }
	// RVA: 0x6896e94 VA: 0x7598eaee94
	public ArgumentCache get_arguments() { }
	// RVA: 0x6896e9c VA: 0x7598eaee9c
	public Boolean IsValid() { }
	// RVA: 0x6896ed8 VA: 0x7598eaeed8
	public BaseInvokableCall GetRuntimeCall(UnityEventBase theEvent) { }
	// RVA: 0x6897380 VA: 0x7598eaf380
	private static BaseInvokableCall GetObjectCall(Object target, MethodInfo method, ArgumentCache arguments) { }
	// RVA: 0x6897800 VA: 0x7598eaf800
	public Void OnBeforeSerialize() { }
	// RVA: 0x6897824 VA: 0x7598eaf824
	public Void OnAfterDeserialize() { }
	// RVA: 0x6897848 VA: 0x7598eaf848
	public Void .ctor() { }
}
```