```go
func getArticle(w word) string {
  if isName(word) {
    return "-"
  }

  if isObject(word) && isCountable(word) {
    if isExactlyThisOne(word) {
      return "the"
    }
    
    return "any"
  }
}


