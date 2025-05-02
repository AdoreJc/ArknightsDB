# MonoBehaviour

**Namespace:** `UnityEngine`


## Properties

- `Boolean useGUILayout`


## Methods

- `Boolean IsInvoking()`

- `Void CancelInvoke()`

- `Void Invoke(String, Single)`

- `Void InvokeRepeating(String, Single, Single)`

- `Void CancelInvoke(String)`

- `Boolean IsInvoking(String)`

- `Coroutine StartCoroutine(String)`

- `Coroutine StartCoroutine(String, Object)`

- `Coroutine StartCoroutine(IEnumerator)`

- `Coroutine StartCoroutine_Auto(IEnumerator)`

- `Void StopCoroutine(IEnumerator)`

- `Void StopCoroutine(Coroutine)`

- `Void StopCoroutine(String)`

- `Void StopAllCoroutines()`

- `Boolean get_useGUILayout()`

- `Void set_useGUILayout(Boolean)`

- `Coroutine StartCoroutineManaged(String, Object)`

- `Coroutine StartCoroutineManaged2(IEnumerator)`

- `Void StopCoroutineManaged(Coroutine)`

- `Void StopCoroutineFromEnumeratorManaged(IEnumerator)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class MonoBehaviour : Behaviour
{

	public Boolean useGUILayout { get; set; }

	// RVA: 0x6885988 VA: 0x7598e9d988
	public Boolean IsInvoking() { }
	// RVA: 0x6885a00 VA: 0x7598e9da00
	public Void CancelInvoke() { }
	// RVA: 0x6885a78 VA: 0x7598e9da78
	public Void Invoke(String methodName, Single time) { }
	// RVA: 0x6885b2c VA: 0x7598e9db2c
	public Void InvokeRepeating(String methodName, Single time, Single repeatRate) { }
	// RVA: 0x6885c60 VA: 0x7598e9dc60
	public Void CancelInvoke(String methodName) { }
	// RVA: 0x6885ce8 VA: 0x7598e9dce8
	public Boolean IsInvoking(String methodName) { }
	// RVA: 0x6885d70 VA: 0x7598e9dd70
	public Coroutine StartCoroutine(String methodName) { }
	// RVA: 0x6885d78 VA: 0x7598e9dd78
	public Coroutine StartCoroutine(String methodName, Object value) { }
	// RVA: 0x6885f1c VA: 0x7598e9df1c
	public Coroutine StartCoroutine(IEnumerator routine) { }
	// RVA: 0x6886058 VA: 0x7598e9e058
	public Coroutine StartCoroutine_Auto(IEnumerator routine) { }
	// RVA: 0x688605c VA: 0x7598e9e05c
	public Void StopCoroutine(IEnumerator routine) { }
	// RVA: 0x6886198 VA: 0x7598e9e198
	public Void StopCoroutine(Coroutine routine) { }
	// RVA: 0x68862d4 VA: 0x7598e9e2d4
	public Void StopCoroutine(String methodName) { }
	// RVA: 0x6886318 VA: 0x7598e9e318
	public Void StopAllCoroutines() { }
	// RVA: 0x6886354 VA: 0x7598e9e354
	public Boolean get_useGUILayout() { }
	// RVA: 0x6886390 VA: 0x7598e9e390
	public Void set_useGUILayout(Boolean value) { }
	// RVA: 0x68863d4 VA: 0x7598e9e3d4
	public static Void print(Object message) { }
	// RVA: 0x6885a3c VA: 0x7598e9da3c
	private static Void Internal_CancelInvokeAll(MonoBehaviour self) { }
	// RVA: 0x68859c4 VA: 0x7598e9d9c4
	private static Boolean Internal_IsInvokingAll(MonoBehaviour self) { }
	// RVA: 0x6885ad0 VA: 0x7598e9dad0
	private static Void InvokeDelayed(MonoBehaviour self, String methodName, Single time, Single repeatRate) { }
	// RVA: 0x6885ca4 VA: 0x7598e9dca4
	private static Void CancelInvoke(MonoBehaviour self, String methodName) { }
	// RVA: 0x6885d2c VA: 0x7598e9dd2c
	private static Boolean IsInvoking(MonoBehaviour self, String methodName) { }
	// RVA: 0x6885e8c VA: 0x7598e9de8c
	private static Boolean IsObjectMonoBehaviour(Object obj) { }
	// RVA: 0x6885ec8 VA: 0x7598e9dec8
	private Coroutine StartCoroutineManaged(String methodName, Object value) { }
	// RVA: 0x6886014 VA: 0x7598e9e014
	private Coroutine StartCoroutineManaged2(IEnumerator enumerator) { }
	// RVA: 0x6886290 VA: 0x7598e9e290
	private Void StopCoroutineManaged(Coroutine routine) { }
	// RVA: 0x6886154 VA: 0x7598e9e154
	private Void StopCoroutineFromEnumeratorManaged(IEnumerator routine) { }
	// RVA: 0x688642c VA: 0x7598e9e42c
	internal String GetScriptClassName() { }
	// RVA: 0x6886468 VA: 0x7598e9e468
	public Void .ctor() { }
}
```