web: export JAVA_OPTS="$JAVA_OPTS -Dhttp.port=$PORT" && build/stage/playBinary/bin/playBinary 
#web: build/stage/playBinary/bin/playBinary -Dhttp.port=${PORT} 
console: build/stage/playBinary/bin/playBinary -gradle -main scala.tools.nsc.MainGenericRunner -usejavacp
