# Changelog

## master (unreleased)
	
## New Features
    
### Changes
	
### Bugs fixed

## 0.1.35 (26-12-2022)
	
## New Features
    
### Changes

	- Don't instrument record map forms which breaks some macroexpansions
	- Do not automatically convert big maps into sorted maps while instrumenting them
	
### Bugs fixed

## 0.1.31 (16-12-2022)
	
## New Features
    
### Changes

### Bugs fixed

- Fix important compilation error when ClojureScript isn't in the path

## 0.1.29 (09-12-2022)
	
## New Features

	- Add normalize-gensyms? undocumented config option
	
### Changes

### Bugs fixed

## 0.1.26 (08-12-2022)
	
## New Features

	- instrument-namespaces-* now returns the a map with :inst-fns and :affected-namespaces

### Changes

### Bugs fixed

## 0.1.24 (29-11-2022)
	
## New Features

### Changes

### Bugs fixed

	- Fix ClojureScript go blocks instrumentation
	
## 0.1.20 (23-11-2022)
	
## New Features

	- instrument-var-clj and instrument-var-shadow-cljs now accept :deep? true for recursively instrumenting referenced vars    
	
### Changes

### Bugs fixed
    
## 0.1.17 (14-11-2022)
