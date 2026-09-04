package main
import (
        "fmt"
        "time"
)

func main(){
    timeNow := time.Now()
    curYear := timeNow.Year()
    newYear := time.Date(curYear+1, 1, 1, 0, 0, 0, 0, timeNow.Location())
    dur := newYear.Sub(timeNow)
    
    days := int(dur.Hours() / 24)
	
	fmt.Printf("Ответ: %d", days)
    
}
