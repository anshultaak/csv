package file
@Grab('com.xlson.groovycsv:groovycsv:1.3')
import static com.xlson.groovycsv.CsvParser.parseCsv
 
fh = new File('file1.csv')
def csv_content = fh.getText('utf-8')
 
def data_iterator = parseCsv(csv_content)
// println data_iterator.getClass()  // class com.xlson.groovycsv.CsvIterator
 

for (line in data_iterator) {
     output = line[2]
     if(output == line[1]) {
         println "value is match"
     } else { 
         println "value is not match"
     }
}
