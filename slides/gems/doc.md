## Doc
<img src="lib/images/doc-test.svg" style="height:45vh"/>   

<!--
/// Divides two numbers.
///
/// # Examples
///
/// ```
/// use dxp::div;
/// let result = div(10, 2);
/// assert_eq!(result, 5);
/// ```
///
/// # Panics
///
/// `div panics if the second argument is zero.
///
/// ```rust,should_panic
/// // panics on division by zero
/// use dxp::div;
/// div(10, 0);
/// ```
pub fn div(a: i32, b: i32) -> i32 {
    if b == 0 { panic!("Divide-by-zero error"); }
    a / b
}-->
