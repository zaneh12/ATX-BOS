# Financial Functions
Compound_Interest <- function(p,n,a,i){
  i <- (i*.01)
  d <- (i/(1+i))
  return((p+a/d)*(1+i)^n−(a/d))
}
Doubling_Time <- function(interest_rate){
  return(log(2)/(log(1+.01*interest_rate)))
}
