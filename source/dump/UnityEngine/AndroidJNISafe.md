# AndroidJNISafe

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.AndroidJNIModule.dll
// Namespace : UnityEngine
internal class AndroidJNISafe
{


	// RVA: 0x6840b7c VA: 0x7598e58b7c
	public static Void CheckException() { }
	// RVA: 0x68344dc VA: 0x7598e4c4dc
	public static Void DeleteGlobalRef(IntPtr globalref) { }
	// RVA: 0x68347c8 VA: 0x7598e4c7c8
	public static Void DeleteWeakGlobalRef(IntPtr globalref) { }
	// RVA: 0x6838250 VA: 0x7598e50250
	public static Void DeleteLocalRef(IntPtr localref) { }
	// RVA: 0x6838e4c VA: 0x7598e50e4c
	public static IntPtr NewString(String chars) { }
	// RVA: 0x6840ed4 VA: 0x7598e58ed4
	public static String GetStringChars(IntPtr str) { }
	// RVA: 0x68384f4 VA: 0x7598e504f4
	public static IntPtr GetObjectClass(IntPtr ptr) { }
	// RVA: 0x6838ab4 VA: 0x7598e50ab4
	public static IntPtr GetStaticMethodID(IntPtr clazz, String name, String sig) { }
	// RVA: 0x6838c08 VA: 0x7598e50c08
	public static IntPtr GetMethodID(IntPtr obj, String name, String sig) { }
	// RVA: 0x683cc28 VA: 0x7598e54c28
	public static IntPtr GetFieldID(IntPtr clazz, String name, String sig) { }
	// RVA: 0x683cce0 VA: 0x7598e54ce0
	public static IntPtr GetStaticFieldID(IntPtr clazz, String name, String sig) { }
	// RVA: 0x683c528 VA: 0x7598e54528
	public static IntPtr FromReflectedMethod(IntPtr refMethod) { }
	// RVA: 0x6837190 VA: 0x7598e4f190
	public static IntPtr FindClass(String name) { }
	// RVA: 0x6838300 VA: 0x7598e50300
	public static IntPtr NewObject(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6840f74 VA: 0x7598e58f74
	public static Void SetStaticObjectField(IntPtr clazz, IntPtr fieldID, IntPtr val) { }
	// RVA: 0x6841030 VA: 0x7598e59030
	public static Void SetStaticStringField(IntPtr clazz, IntPtr fieldID, String val) { }
	// RVA: 0x68410ec VA: 0x7598e590ec
	public static Void SetStaticCharField(IntPtr clazz, IntPtr fieldID, Char val) { }
	// RVA: 0x68411a8 VA: 0x7598e591a8
	public static Void SetStaticDoubleField(IntPtr clazz, IntPtr fieldID, Double val) { }
	// RVA: 0x6841264 VA: 0x7598e59264
	public static Void SetStaticFloatField(IntPtr clazz, IntPtr fieldID, Single val) { }
	// RVA: 0x6841320 VA: 0x7598e59320
	public static Void SetStaticLongField(IntPtr clazz, IntPtr fieldID, Int64 val) { }
	// RVA: 0x68413dc VA: 0x7598e593dc
	public static Void SetStaticShortField(IntPtr clazz, IntPtr fieldID, Int16 val) { }
	// RVA: 0x6841498 VA: 0x7598e59498
	public static Void SetStaticSByteField(IntPtr clazz, IntPtr fieldID, SByte val) { }
	// RVA: 0x6841554 VA: 0x7598e59554
	public static Void SetStaticBooleanField(IntPtr clazz, IntPtr fieldID, Boolean val) { }
	// RVA: 0x6841610 VA: 0x7598e59610
	public static Void SetStaticIntField(IntPtr clazz, IntPtr fieldID, Int32 val) { }
	// RVA: 0x68416cc VA: 0x7598e596cc
	public static IntPtr GetStaticObjectField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x6841774 VA: 0x7598e59774
	public static String GetStaticStringField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x684181c VA: 0x7598e5981c
	public static Char GetStaticCharField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x68418c4 VA: 0x7598e598c4
	public static Double GetStaticDoubleField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x6841978 VA: 0x7598e59978
	public static Single GetStaticFloatField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x6841a2c VA: 0x7598e59a2c
	public static Int64 GetStaticLongField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x6841ad4 VA: 0x7598e59ad4
	public static Int16 GetStaticShortField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x6841b7c VA: 0x7598e59b7c
	public static SByte GetStaticSByteField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x6841c24 VA: 0x7598e59c24
	public static Boolean GetStaticBooleanField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x6841ccc VA: 0x7598e59ccc
	public static Int32 GetStaticIntField(IntPtr clazz, IntPtr fieldID) { }
	// RVA: 0x6838784 VA: 0x7598e50784
	public static Void CallStaticVoidMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6838eec VA: 0x7598e50eec
	public static IntPtr CallStaticObjectMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6839568 VA: 0x7598e51568
	public static String CallStaticStringMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6841d74 VA: 0x7598e59d74
	public static Char CallStaticCharMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6841e2c VA: 0x7598e59e2c
	public static Double CallStaticDoubleMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6841ef0 VA: 0x7598e59ef0
	public static Single CallStaticFloatMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6841fb4 VA: 0x7598e59fb4
	public static Int64 CallStaticLongMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x684206c VA: 0x7598e5a06c
	public static Int16 CallStaticShortMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6842124 VA: 0x7598e5a124
	public static SByte CallStaticSByteMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x68421dc VA: 0x7598e5a1dc
	public static Boolean CallStaticBooleanMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6836c60 VA: 0x7598e4ec60
	public static Int32 CallStaticIntMethod(IntPtr clazz, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6842294 VA: 0x7598e5a294
	public static Void SetObjectField(IntPtr obj, IntPtr fieldID, IntPtr val) { }
	// RVA: 0x6842350 VA: 0x7598e5a350
	public static Void SetStringField(IntPtr obj, IntPtr fieldID, String val) { }
	// RVA: 0x684240c VA: 0x7598e5a40c
	public static Void SetCharField(IntPtr obj, IntPtr fieldID, Char val) { }
	// RVA: 0x68424c8 VA: 0x7598e5a4c8
	public static Void SetDoubleField(IntPtr obj, IntPtr fieldID, Double val) { }
	// RVA: 0x6842584 VA: 0x7598e5a584
	public static Void SetFloatField(IntPtr obj, IntPtr fieldID, Single val) { }
	// RVA: 0x6842640 VA: 0x7598e5a640
	public static Void SetLongField(IntPtr obj, IntPtr fieldID, Int64 val) { }
	// RVA: 0x68426fc VA: 0x7598e5a6fc
	public static Void SetShortField(IntPtr obj, IntPtr fieldID, Int16 val) { }
	// RVA: 0x68427b8 VA: 0x7598e5a7b8
	public static Void SetSByteField(IntPtr obj, IntPtr fieldID, SByte val) { }
	// RVA: 0x6842874 VA: 0x7598e5a874
	public static Void SetBooleanField(IntPtr obj, IntPtr fieldID, Boolean val) { }
	// RVA: 0x6842930 VA: 0x7598e5a930
	public static Void SetIntField(IntPtr obj, IntPtr fieldID, Int32 val) { }
	// RVA: 0x68429ec VA: 0x7598e5a9ec
	public static IntPtr GetObjectField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842a94 VA: 0x7598e5aa94
	public static String GetStringField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842b3c VA: 0x7598e5ab3c
	public static Char GetCharField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842be4 VA: 0x7598e5abe4
	public static Double GetDoubleField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842c98 VA: 0x7598e5ac98
	public static Single GetFloatField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842d4c VA: 0x7598e5ad4c
	public static Int64 GetLongField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842df4 VA: 0x7598e5adf4
	public static Int16 GetShortField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842e9c VA: 0x7598e5ae9c
	public static SByte GetSByteField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842f44 VA: 0x7598e5af44
	public static Boolean GetBooleanField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x6842fec VA: 0x7598e5afec
	public static Int32 GetIntField(IntPtr obj, IntPtr fieldID) { }
	// RVA: 0x68386c8 VA: 0x7598e506c8
	public static Void CallVoidMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6839408 VA: 0x7598e51408
	public static IntPtr CallObjectMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6843094 VA: 0x7598e5b094
	public static String CallStringMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x684314c VA: 0x7598e5b14c
	public static Char CallCharMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6843204 VA: 0x7598e5b204
	public static Double CallDoubleMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x68432c8 VA: 0x7598e5b2c8
	public static Single CallFloatMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x684338c VA: 0x7598e5b38c
	public static Int64 CallLongMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6843444 VA: 0x7598e5b444
	public static Int16 CallShortMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x68434fc VA: 0x7598e5b4fc
	public static SByte CallSByteMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x68435b4 VA: 0x7598e5b5b4
	public static Boolean CallBooleanMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x684366c VA: 0x7598e5b66c
	public static Int32 CallIntMethod(IntPtr obj, IntPtr methodID, jvalue[] args) { }
	// RVA: 0x6843724 VA: 0x7598e5b724
	public static Char[] FromCharArray(IntPtr array) { }
	// RVA: 0x68437c4 VA: 0x7598e5b7c4
	public static Double[] FromDoubleArray(IntPtr array) { }
	// RVA: 0x6843864 VA: 0x7598e5b864
	public static Single[] FromFloatArray(IntPtr array) { }
	// RVA: 0x6843904 VA: 0x7598e5b904
	public static Int64[] FromLongArray(IntPtr array) { }
	// RVA: 0x68439a4 VA: 0x7598e5b9a4
	public static Int16[] FromShortArray(IntPtr array) { }
	// RVA: 0x6843a44 VA: 0x7598e5ba44
	public static Byte[] FromByteArray(IntPtr array) { }
	// RVA: 0x6843ae4 VA: 0x7598e5bae4
	public static SByte[] FromSByteArray(IntPtr array) { }
	// RVA: 0x6843b84 VA: 0x7598e5bb84
	public static Boolean[] FromBooleanArray(IntPtr array) { }
	// RVA: 0x6843c24 VA: 0x7598e5bc24
	public static Int32[] FromIntArray(IntPtr array) { }
	// RVA: 0x683c130 VA: 0x7598e54130
	public static IntPtr ToObjectArray(IntPtr[] array, IntPtr type) { }
	// RVA: 0x683bfe8 VA: 0x7598e53fe8
	public static IntPtr ToCharArray(Char[] array) { }
	// RVA: 0x683bf48 VA: 0x7598e53f48
	public static IntPtr ToDoubleArray(Double[] array) { }
	// RVA: 0x683bea8 VA: 0x7598e53ea8
	public static IntPtr ToFloatArray(Single[] array) { }
	// RVA: 0x683be08 VA: 0x7598e53e08
	public static IntPtr ToLongArray(Int64[] array) { }
	// RVA: 0x683bd68 VA: 0x7598e53d68
	public static IntPtr ToShortArray(Int16[] array) { }
	// RVA: 0x683bc28 VA: 0x7598e53c28
	public static IntPtr ToByteArray(Byte[] array) { }
	// RVA: 0x683bcc8 VA: 0x7598e53cc8
	public static IntPtr ToSByteArray(SByte[] array) { }
	// RVA: 0x683bb88 VA: 0x7598e53b88
	public static IntPtr ToBooleanArray(Boolean[] array) { }
	// RVA: 0x683bae8 VA: 0x7598e53ae8
	public static IntPtr ToIntArray(Int32[] array) { }
	// RVA: 0x6839ff0 VA: 0x7598e51ff0
	public static IntPtr GetObjectArrayElement(IntPtr array, Int32 index) { }
	// RVA: 0x6839f50 VA: 0x7598e51f50
	public static Int32 GetArrayLength(IntPtr array) { }
}
```