# Car Troubleshooting Expert System

## 1.Overview

The Car Troubleshooting Expert System is a rule-based web application that helps users identify common vehicle problems and provides suitable solutions based on reported symptoms. The system simulates expert-level reasoning using predefined rules and logical inference.

## 2.Purpose

The main purpose of this project is to assist car owners in understanding basic vehicle issues without requiring immediate professional help. It reduces manual inspection effort and acts as a decision-support system for early diagnosis.

## 3.Tools Used

Frontend: React (Vite) with TailwindCSS

Backend: Python (Flask)

Communication: Axios (REST API)

Logic: Rule-based IF–ELSE inference engine

## 4.Working

The user selects or enters car details and symptoms through the React frontend.

The data is sent to the Flask backend via API requests.

The backend applies IF–ELSE rules to match symptoms with known problems.

The system returns the identified cause and recommended solution.

A domain-specific chatbot allows users to ask major car-related queries and retrieve relevant solutions.

## 5.Conclusion

This expert system provides a simple and efficient approach to diagnosing common car problems. By combining rule-based logic with a modern web interface, it offers quick and reliable troubleshooting assistance for users.

## 6.Deployment

Live Demo: https://car-expert-system.vercel.app/
